# Køge Bugt Ice Dynamics 

## Ice Surface Velocity 
A timeseries of ice velocity was extracted across Køge Bugt N, Køge Bugt C, and Køge Bugt S, using NASA’s MEaSUREs Inter-mission Time Series of Land Ice Velocity and Elevation (ITS_LIVE) product (https://its-live.jpl.nasa.gov/). We employed the beta Version-2 ITS_LIVE image-pairs (Gardner et al., 2024) that include surface velocities derived from Landsat -4, -5, -7, -8, -9 (Gardner et al., 2018), Sentinel-1A/-1B, and Sentinel-2A/-2B (Lei et al., 2022). The maximum time interval for each given image-pair was set to 12 days. Ice velocity was sampled at 3 km intervals along the centreline of each respective glacier (T, T3, T6, T9). 

## Ice Discharge 
A timeseries of solid ice discharge from Køge Bugt N, Køge Bugt C, and Køge Bugt S, was extracted from Mankoff et al. (2020), provided on the GEUS dataverse (https://doi.org/10.22008/promice/data/ice_discharge/d/v02). This dataset provides estimates of ice discharge through algorithmically generated gates positioned ~ 5 km upstream from the baseline terminus of all fast-flowing ice (>100 m/yr).

## Terminus Position
Terminus positions derived between 2016 and 2022 were downloaded from the MEaSUREs Weekly to Monthly Greenland Outlet Glacier Terminus Positions from Sentinel-1 Mosaics (2018-2022; https://nsidc.org/data/nsidc-0781/versions/1). Terminus positions derived between 2022 and 2024 were then manually digitised from Landsat-8 and Landsat-9 imagery; where suitable optical imagery was unavailable, MEaSUREs Sentinel-1A and Sentinel-1B synthetic aperture radar (SAR) mosaics were employed (https://doi.org/10.5067/WXQ366CP8YDE). Terminus position change was conducted using MaQiT (https://liverpoolgee.wordpress.com/maqit/), using the curvilinear box method. 

# Bed Elevation 
Bed elevation profiles were sampled from BedMachine v5 (Morlighem et al., 2022; https://doi.org/10.5067/GMEVBWFLWA7X), along the central flowlines of Køge Bugt N, Køge Bugt C and Køge Bugt S, respectively. 

# Ice Surface Elevation 
For the ice surface profiles shown in Figure 2a, 3a, and 4a, ice elevation was sampled from BedMachine v5 (Morlighem et al., 2022). For more detailed analysis, 2-m resolution ArcticDEM strips (Porter et al., 2022) were downloaded and co-registered using the pDEMtools software package (Chudley & Howat, 2024; https://github.com/trchudley/pdemtools). 

## Surface Runoff 
Monthly estimates of cumulative surface runoff were extracted across the hydrological basins of each outlet glacier from Mankoff (2020), provided on the GEUS dataverse (https://doi.org/10.22008/promice/data/ice_discharge/d/v02). These estimates were derived from two regional climate models (RCMs): (i) Modèle Atmosphérique Régional (MAR), and (ii) Regional Atmospheric Climate Model (RACMO). 

## Ocean Thermal Forcing 
Ocean thermal forcing was estimated at each glacier using TOPAZ4b reanalysis data provided by the Copernicus Marine Service (Arctic Ocean Physics Reanalysis, 2024; https://doi.org/10.48670/moi-00007). For each glacier, mean monthly sea water potential temperature and practical salinity were sampled at the effective depth defined by Slater et al. (2020). Pressure, absolute salinity and in-situ temperature were then calculated using functions defined by the Gibbs SeaWater Oceanographic Toolbox (McDougall and Barker, 2011). 

