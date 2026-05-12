# EARTH-211-Project
POTENTIAL RESEARCH QUESTIONS:

**How does the maximum monthly ocean water temperature vary across regions of the Gulf of Mexico and the Atlantic coast of the United States, and how does the regional variation of ocean water temperature relate to which states experience the most frequent hurricanes?**

For this question, I would investigate how increased ocean water temperatures are related to increased hurricane activity in states near the Atlantic coast and the Gulf of Mexico, as these states, such as Texas, Florida, and the Carolinas, experience the most frequent hurricanes. I picked this question because I experienced a lot of hurricanes growing up, and have been curious about how they form, and why some places are more prone to hurricanes than others. One factor that leads to hurricane formation is warm ocean waters, so answering this question would help me to understand how ocean warming due to climate change may lead to increased hurricane frequency and intensity. I will have to know the day/month/year of data collection, the location of data collection, the water temperature recorded (perhaps looking for highest daily/monthly temp will make organizing my data easier), hurricane strength category/max. windspeed/other measure of storm strength, storm frequency (may need to calculate by hand), etc. I may use the NOAA's ADT-HURSAT dataset for hurricane data, and NASA's sea surface temperature datasets and/or NOAA's GLobalTemp dataset for water temperature data. I may look into time series analysis to track changes across years to see if ocean temperatures or hurricane frequency has increased in the past few decades. 


**How does increased urbanization in the Pacific Northwest affect pollinator populations and species diversity?**

For this question, I would investigate the extent to which increased urbanization has a negative effect on pollinator populations in the Pacific Northwest. I chose this question because the decline of pollinator populations is a serious environmental issue that has negative implications for plant biodiversity and global food security, so it is important to understand the factors driving pollinator decline. I would investigate the Pacific Northwest in particular because I found a good dataset with detailed data from that region. I would need to have some way to measure urbanization, like population density or land cover. I would also need to know pollinator abundance and diversity for each region of data collection. I may want to use the USGS National Land Cover database, or the Census.gov population density database. I would also find datasets about pollinator diversity, like one that I found from the Ecological Society of America. I would probably want to compare the pollinator status in highly urbanized spaces with less urbanized/more natural spaces to see how they differ, perhaps using comparative population testing as well.

DATA COLLECTION:
For each of the possible research questions, begin collecting or locating relevant data. You should provide:

The name of the dataset.
The source or website where the data came from.
The spatial and/or temporal coverage, if applicable.
The main variables you expect to use.
The file format, such as CSV, NetCDF, shapefile, etc.

**Research Question 1: (Hurricanes)**
Note: Many of these datasets are too big to be downloaded! All links are included for access to datasets.

Link: https://www.nhc.noaa.gov/data/#hurdat
Name: Atlantic hurricane database (HURDAT2) 1851-2025
Source: National Hurricane Center - NOAA
Temporal coverage: 1851-2025 
Main variables: Year/Month/Day of report, storm category, numerical category, max. windspeed
File format: .txt

Link: https://www.ncei.noaa.gov/products/land-based-station/noaa-global-temp 
Name: NOAAGlobalTemp v. 6.1
Source: National Centers for Environmental Information - NOAA
File format: NetCDF (need to find an application that can open these types of files)

Link: https://www.ncei.noaa.gov/products/land-based-station/noaa-global-temp 
Name: NOAAGlobalTemp v. 6.1 Time Series
Source: National Centers for Environmental Information - NOAA
Main variables: Year or month, anomaly of temperature
File format: NetCDF

Link: https://www.earthdata.nasa.gov/topics/ocean/sea-surface-temperature/data-access-tools 
Source: NASA Earth Data
Name of Dataset: AIRS/Aqua L2 Near Real Time (NRT) Standard Physical Retrieval (AIRS-only) V006 (AIRS2RET_NRT) at GES DISC
Spatial coverage: N: 90 S: -90 E: 180 W: -180
Temporal coverage: 2016-10-15 to Present

**Research Question 2: (Pollinators)**

* Dataset can be accessed via this link - it is too large to be downloaded.
Link: https://www.sciencebase.gov/catalog/item/655ceb8ad34ee4b6e05cc51a 
Name: Annual National Land Cover Database (NLCD) Collection 1 Products (ver. 1.1, June 2025)
Source: USGS
Temporal coverage: 1985-2024

Link: https://datadryad.org/dataset/doi:10.5061/dryad.ffbg79cwn
Name: A dataset for pollinator diversity and their interactions with plants in the Pacific NorthWest
Source: Dryad
Temporal coverage: 2005-2017
Main variables: pollinator species, day/month/year collected, location description/name, lat/long
File format: csv


