# Hack the Bay: Data
This repo is intended to provide data and starter code for the [Hack the Bay](https://hack-the-bay.devpost.com) hackathon (Aug. 3-Sep. 14, 2020). 

[DOWNLOAD WATER QUALITY & BENTHIC DATA HERE](https://drive.google.com/drive/folders/19HYUC5SLj7EV3Ui4fMhHBk_hnxcSY-PJ?usp=sharing)

## Overview
CMC’s data is intended to fill spatial and temporal data gaps that exist in the federal Chesapeake Bay Program’s (CBP) database. Both CMC and CBP measure the health of the watershed through monitoring both chemical water quality indicators and counting the presence of different benthic organisms. For all hackathon challenges, we recommend participants use both CMC and CBP water quality data (and for challenges 1 and 2, also recommend leveraging CMC and CBP benthic sample data). We have downloaded water quality and benthic datasets here and made them available in the Google Drive folder linked above. In addition to these datasets, there are links to more suggested datasets for each challenge below. 

*Note on the data: For CBP, only data after 2005 is included (for both water quality and benthic data). CMC data goes back to 1992. For more historic CBP data, you can download additional [water quality data](http://data.chesapeakebay.net/WaterQuality) and [nontidal benthic sample data](http://data.chesapeakebay.net/LivingResources) directly from CBP. CMC data was downloaded from the [Chesapeake Data Explorer](https://cmc.vims.edu/#/home/query/). 

## Contents
  1. Data to Download [Google Drive]
      - [Water Quality Data](https://drive.google.com/file/d/12uoFlcn8pgeuxD2-seFak36KTvrFPKCt/view?usp=sharing)
      - [Benthic Sample Data](https://drive.google.com/drive/folders/1fq87d3k4pnyhbhu06dFO5XEanAjXCDry?usp=sharing) **Stream Health Data now available!**
  2. [Recommended Datasets](#recommended-datasets)
  3. [Data Dictionaries](#data-dictionaries)
  4. [Understanding the Data](#understanding-the-data)
  5. [Code for Generating Final Datasets](https://github.com/Hack-the-Bay/hack-the-bay/tree/master/Code)

## Recommended Datasets
X = primary dataset (strongly recommended)

o = optional (suggested)

| Source | Dataset | Challenge 1 | Challenge 2 | Challenge 3 | Challenge 4 |
|--------|---------|-------------|-------------|-------------|-------------|
| CBP / CMC | [Water Quality](https://drive.google.com/file/d/1M4ELFR6cS32EvxHlRjGNr9TYXN84O2ce/view?usp=sharing) | X | X | X | X |
| CBP / CMC | [Benthic](https://drive.google.com/drive/folders/1fq87d3k4pnyhbhu06dFO5XEanAjXCDry?usp=sharing) | X | X | o | o |
| USGS | [Stream Flow](https://waterdata.usgs.gov/nwis/rt) | o | o | o | |
| Water Quality Portal | [Water Quality Portal](https://www.waterqualitydata.us)| o | | o | |
| USGS | [Pollution Yields and Loads](https://cbrim.er.usgs.gov/trends_query.html?sorts%5Bstaid%5D=1&sorts%5Bpcode%5D=1&sorts%5Bstart_Year%5D=1&sorts%5Bend_Year%5D=1&sorts%5Bnyears%5D=1&sorts%5Bperiod%5D=1&sorts%5Blowf%5D=1&sorts%5Bestf%5D=1&sorts%5Bupf%5D=1&sorts%5Bfnt_Pct%5D=1&sorts%5BtrendDir%5D=1&sorts%5Blikelihood%5D=1) | o | | o | |
| USGS | [Geology](https://ngmdb.usgs.gov/Prodesc/proddesc_9215.htm) | o | | o | |
| NOAA | [Weather](https://www.ncdc.noaa.gov/cdo-web/) | | | o | |
| CBP | [CAST - Nutrient Point Source/Best Management Practices Database](https://cast.chesapeakebay.net/) | o | | o | |
| Chesapeake Conservancy | [Land Cover](https://www.chesapeakeconservancy.org/conservation-innovation-center/high-resolution-data/land-cover-data-project/)| o | | o | |
| USGS | [Land Use Over Time](https://www.usgs.gov/centers/eros/science/national-land-cover-database)| o | | o | | 
| CBP | [Watershed Data Dashboard](https://gis.chesapeakebay.net/wip/dashboard)| o | | o | |
| CBP | [Chesapeake Bay Open GIS Data](http://data-chesbay.opendata.arcgis.com/)| o | | o | |
| CBP | [Public Access Data](https://www.chesapeakebay.net/what/data) (Under GIS Datasets)| | | | o |
| EPA | [How's My Water?](https://mywaterway.epa.gov/)| o | | | o |
| EPA | [EnviroAtlas](https://www.epa.gov/enviroatlas)| o | | o | o |
| Chesapeake Conservancy | [Land Use](https://chesapeakeconservancy.org/conservation-innovation-center/high-resolution-data/land-use-data-project/) | o | | o | |
| CBP | [Healthy Watersheds Assessment (see references at end)](https://www.chesapeakebay.net/channel_files/26540/chesapeake_healthy_watersheds_assessment_report.pdf)| o | | o | o |
| EPA | [Chesapeake Bay Environmental Justice (EJ) Screen](https://gis.chesapeakebay.net/cbpejscreen/) | | | | o |
| CDC | [Social Vulnerability Index](https://svi.cdc.gov/data-and-tools-download.html) | | | | o |
| US Census | [Demographic / Economic Data](https://www.census.gov/data.html) | | | | o |
| US Census | [County Boundary Maps](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-nation-u-s-current-county-and-equivalent-national-shapefile) | | | | X |
| USDA | [HUC12 Boundary Maps](https://nrcs.app.box.com/v/huc/file/532373547877) | X | X | X | o |

## Data Dictionaries
  - [CMC Data Dictionary](https://www.chesapeakemonitoringcoop.org/wp-content/uploads/2020/07/Data-Dictionary_June-2020.pdf)
    - [Problem Codes](https://github.com/Hack-the-Bay/hack-the-bay/blob/master/problemCodes.csv)
    - [Qualifier Codes](https://github.com/Hack-the-Bay/hack-the-bay/blob/master/qualifierCodes.csv)
  - [CMC Water Quality Data Rubric](https://www.chesapeakemonitoringcoop.org/wp-content/uploads/2018/11/CMC-Water-Quality-Data-Rubric_6.18.2020.pdf) - this document explains the three tiers of data in CMC's database
  - [CBP Data Dictionary](https://www.chesapeakebay.net/documents/3676/cbwqdb2004_rb.pdf)
  - [Mapping of CMC Parameters to CBP Parameters](https://github.com/Hack-the-Bay/hack-the-bay/blob/master/CBP_water_dictionary_final.csv)
  - [Instructions for Formatting Benthic Data for Chessie BB](https://github.com/Hack-the-Bay/hack-the-bay/blob/master/ChessieBB_Instructions.xlsx)
  - [Link to Chessie BIBI for Processing Benthic Data](https://rstudio-pubs-static.s3.amazonaws.com/462489_8d2734925de3492eb294b64f54a260af.html)
  
## Understanding the Data

### Geospatial Density
The Chesapeake Bay watershed spans Virginia, Maryland, Delaware, West Virginia, Pennsylvania, New York and Washington, DC. CMC’s data has greater coverage in some states over others, and is largely dependent on the activity level and participation of monitoring groups in those states.  As of July 2020, CMC’s water quality database included samples from over 1,600 unique collection points (compared to 887 unique collection points in CBP’s database from 2005-2020). 

![Geospatial Data](https://github.com/Hack-the-Bay/hack-the-bay/blob/master/images/HTB_geo.png)

### Temporal Density
CMC’s water quality data goes back as far as 1992, with the majority of their data collected after 2017. 

![Temporal Data](https://github.com/Hack-the-Bay/hack-the-bay/blob/master/images/HTB_time.png)

### What is a Data Gap?
Participants exploring CMC’s data for the first time will notice that data collection is highly variable across time, space, and water quality parameter. Data sparsity is a reality of many environmental datasets. When planning your analysis, each challenge recommends focusing on either a geographic area or one of a few parameters that can be compared across space/time.   

To tell a story across space, we need data that effectively covers a region with samples to represent the condition of the area. 
  - It is important to represent different habitats and land uses like forest, agricultural fields and urban settings.
  - Other habitats might be valuable to represent such as headwater streams versus lowland streams, or ponds and reservoirs versus rivers and bays, as examples of locating land use and land cover categories that show an abundance of data versus data gaps.

To tell a story across time, we need data collected seasonally and annually so that change over time can be evaluated. Trends in time tend to require at least 4 years of data while time trends necessitating 10 or more years of data are very valuable. 
  - CMC is most interested in locations that have collected data in the last 5 years. (Locations with robust historic data that have not collected new data in the last five years would be considered a gap.)
  - The ideal sampling cadence is at least 10x per year for water quality and 1x per year, during the same season each year, for benthic samples. 

### Selecting Locations
If you select a challenge that recommends picking a specific part of the watershed to focus your analysis on, consider some ways that the watershed could be separated geographically:
-	Hydrologic Unit Code (HUC): HUCs are a specific type of boundary for bodies of water that range in detail from HUC-2 (2-digit HUC) to HUC-12 (12-digit HUC). For environmental analyses, evaluating parts of the watershed by HUC-12 is recommended (ex., for Challenges 1, 2, and 3).
-	County / Municipality: Using administrative boundaries makes sense when comparing environmental data to social and demographic data (ex., for Challenge 4).
  
## Code
This repo contains notebooks with the code used to join the raw exported datasets from CMC and CBP, as well as add HUC12 and FIPS codes.

## Questions?
If you have any questions about the data or information in this repo, contact Kate Dowdy (dowdy_katherine@bah.com). More resources for the Hack the Bay hackathon can be found [here](https://hack-the-bay.devpost.com/details/resources). 
