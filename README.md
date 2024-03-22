**An Open Geological Database- A wide collection of Geological, Mining, and Seismic datasets for open research.**

**Explore datasets, share feedback**

**Submit your own datasets with the following fields-**

**A. Location-** This field indicates whether the dataset is collected from a particular location or country. However, several datasets are collected from multiple locations. Specifying the location enables the users to obtain data as per their requirements.

**B. Type-** This field can mention the sensor that captured the dataset, or specify the type/ application of the dataset.

**C. Description-** This field may contain a short summary of the specification, application, and utility of the dataset so that both the experts, and the general readers can explore, and use these datasets.

**D. Tags-** Mention specific keywords that give an overview of the data, and facilitate easy searching.

**E. Link-** It mentions the links to the websites hosting the datasets. We intend to maintain and update the links from time to time.

**List of Datasets in OGD**

**Dataset Description**

**Location-** Greece

**Type-** Multispectral

**Description-** Machine Learning (ML) algorithms have successfully contributed in the creation of automated methods of recognizing patterns in high-dimensional data. Remote sensing data covers wide geographical areas and could be used to solve the problem of the demand of various in-situ data. Lithological mapping using remotely sensed data is one of the most challenging applications of ML algorithms. In the framework of the “AI for Geoapplications” project, ML and especially Deep Learning (DL) methodologies are investigated for the identification and characterization of the lithology based on remote sensing data in various pilot areas in Greece. In order to train and test the various ML algorithms, a dataset consisting of 27 ROIs selected mainly from low -vegetated areas, that cover 2% of the total area of Greece was created.

**Tags-** Classification, Semantic segmentation, Multisensor data fusion

**Link-** https://doi.org/10.5281/zenodo.7806929

**Dataset for Lithological Mapping**

**Location-** California

**Description-**

This dataset contains over one thousand high-resolution images of aerial photographs taken in southern California. The photographs were taken from a plane and are meant as a reasonable facsimile for satellite images. Images are grouped into sets of five, each of which have the same set. Each image in a set was taken on a different day (but not necessarily at the same time each day). The images for each set cover approximately the same area but are not exactly aligned. Images are named according to the convention setId_day. In the training set, the images have the correct day ordering. In the test set, the images are scrambled.

This competition asks you order the scrambled images in the test set. This is anticipated to be a challenging task. Some locations will provide very little evidence of changes from day to day. Other locations will have subtle changes that hint at an ordering, such as parked or moving vehicles, differences in bodies of water, or changes in shadows. On account of the difficulty, you may use both manual and computer-based analysis in this competition.

**File/Folder descriptions**

For convenience, we have provided both lossless, high-quality images (train/test) as well as the same images in a compressed jpeg format (train_sm/test_sm). train - 8-bit tif images of the training set train_sm - compressed (lossy) jpegs of the training set test - 8-bit tif images of the test set test_sm - compressed (lossy) jpegs of the training set sample_submission.csv - a sample submission file in the correct format

**Tags-** Mining, Remote Sensing, Satellite Image, Aerial Photograph, Exploration, Minerals

**Link-** https://www.kaggle.com/competitions/draper-satelliteimage-chronology/data

**Draper Satellite Image Chronology**

**Global Coal Mine Tracker**

**Location-** Worldwide

**Description-** The Global Coal Mine Tracker (GCMT) is a worldwide dataset of coal mines and proposed projects. The tracker provides asset-level details on ownership structure, development stage and status, coal type, production, workforce size, reserves and resources, methane emissions, geolocation, and over 30 other categories. The most recent update – published in April 2023 – includes operating mines producing 1 million tonnes per year or more, with smaller mines included at discretion. The tracker also includes proposed coal mines and mine expansions with a designed capacity of 1 million tonnes per year or more. Data is available to download and viewable with interactive mapping and aggregate dashboards and summary tables. Each coal mine is linked to its own separate factsheet on GEM.wiki that provides references and further background, including news about project financing, civil society opposition, labor activity, and workplace accidents. The project methodology is available here. To receive notifications from this project, please sign up for our mailing list. If you have questions about this project, please contact the Project Manager, Ryan Driskell Tate.

**Tags-** Coal Mine, Minerals, Mining

**Link-** https://globalenergymonitor.org/projects/global-coalmine-tracker

**Location-** Worldwide

**Description-**

This portal brings together all of the disclosures that mining companies have made about their tailings storage facilities. It gives communities, investors, regulators, and the media unprecedented access to information about mine waste.

**Tags-** Tailings, Mine, Mineral, Storage Facilities

**Link-** Datalink-https://tailing.grida.no/map/analysis

**Global Tailings Portal Global Mining Dataset**

**Location-** Worldwide

**Description-**

This data set provides spatially explicit estimates of the area directly used for surface mining on a global scale. It contains more than 21,000 polygons of activities related to mining, mainly of coal and metal ores. Several data sources were compiled to identify the approximate location of mines active at any time between the years 2000 to 2017. This data set does not cover all existing mining locations across the globe. The polygons were delineated by experts using Sentinel-2 cloudless (https://s2maps.eu by EOX IT Services GmbH (contains modified Copernicus Sentinel data 2017 & 2018)) and very high-resolution satellite images available from Google Satellite and Bing Imagery. The derived polygons cover the direct land used by mining activities, including open cuts, tailing dams, waste rock dumps, water ponds, and processing infrastructure.

**The ZIP file contains:**

The main data set consists of a GeoPackage (GPKG) file, including the following variables: ISO3_CODE, COUNTRY_NAME, AREA in squared kilometres, FID with the feature ID, and geom in geographical coordinates WGS84. global_mining_polygons_v1.gpkg

The summary of the mining area per country is available in comma-separated values (CSV) file, including the following variables: ISO3_CODE, COUNTRY_NAME, A R E A < d o u b l e > i n s q u a r e d k i l ome t e r s , a n d N_FEATURES number of mapped features. global_mining_area_per_country_v1.csv Grid data sets with the mining area per cell were derived from the polygons. The grid data is available at: 30 arcsecond resolution (approximately 1x1 km at the equator), 5 arc-minute (approximately 10x10 km at the equator), 30 arcminute resolution (We performed an independent validation of the mining data set using control points. For that, we draw a 1,000 random samples stratified between two classes: mine and no-mine. The control points are also available as a GPKG file, including the variables: MAPPED, REFERENCE, FID with the feature ID, and geom in geographical coordinates WGS84. The overall accuracy calculated from the control points was 88.4%. For other accuracy metrics see the source link.

**Tags:** Mines, Mineral, Shapefile, Location, Remote Sensing Image

**Link:** https://doi.pangaea.de/10.1594/PANGAEA.910894

**Quality Prediction in a Mining Process**

**Description-**

It is not always easy to find databases from real-world manufacturing plants, especially mining plants. So, I would like to share this database with the community, which comes from one of the most important parts of a mining process: a flotation plant!

The main goal is to use this data to predict how much impurity is in the ore concentrate. As this impurity is measured every hour, if we can predict how much silica (impurity) is in the ore concentrate, we can help the engineers, giving them early information to take actions (empowering!). Hence, they will be able to take corrective actions in advance (reduce impurity, if that is the case) and also help the environment (reducing the amount of ore that goes to tailings as you reduce silica in the ore concentrate).

**Type-** Mining, Minerals, Ore, Plant, Manufacturing

**Link-** https://www.kaggle.com/datasets/edumagalhaesquality-prediction-in-a-mining-process

**SNL Metals & Mining Location- Worldwide**

**Description-**

The SNL Metals and Mining dataset allows you to explore the in-depth coverage on mining properties and companies, covering a wide array of commodities. Keep track of ongoing sector activities including initial exploration, project developments and commodity production. This dataset includes: Asset-level details on over 35,000 mines, projects and processing facilities worldwide Corporate data and financial metrics for over 3,600 publicly listed mining companies. Historical and forecast commodity supply with Mine Economics - our granular mine-level production and cost models Proprietary research including our global exploration budgets data set.

**Tags-** Metals, Mining

**Link-** https://www.marketplace.spglobal.com/en/datasets/snlmetals-mining-(19)

**Global Mining Locations Data**

**Location-** Worldwide

**Description-** This data set provides spatially explicit estimates of the area directly used for surface mining on a global scale. It contains more than 21,000 polygons of activities related to mining, mainly of coal and metal ores. Several data sources were compiled to identify the approximate location of mines active at any time between the years 2000 to 2017. This data set does not cover all existing mining locations across the globe. The polygons were delineated by experts using Sentinel-2 cloudless (https://s2maps.eu by EOX IT Services GmbH (contains modified Copernicus Sentinel data 2017 & 2018)) and very high-resolution satellite images available from Google Satellite and Bing Imagery. The derived polygons cover the direct land used by mining activities, including open cuts, tailing dams, waste rock dumps, water ponds, and processing infrastructure.

The ZIP file contains: The main data set consists of a GeoPackage (GPKG) file, including the following variables: ISO3_CODE, COUNTRY_NAME, AREA in squared kilometres, FID with the feature ID, and geom in geographical coordinates WGS84. global_mining_polygons_v1.gpkg The summary of the mining area per country is available in comma-separated values (CSV) file, including the following variables: ISO3_CODE, COUNTRY_NAME, AREA in squared kilometers, and N_FEATURES number of mapped features. global_mining_area_per_country_v1.csv Grid data sets with the mining area per cell were derived from the polygons. The grid data is available at: 30 arcsecond resolution (approximately 1x1 km at the equator), 5 arc-minute (approximately 10x10 km at the equator), 30 arcminute resolution (approximately 55x55 km at the equator). global_miningarea_v1_30arcsecond.tif global_miningarea_v1_5arcminute.tif global_miningarea_v1_30arcminute.tif We performed an independent validation of the mining data set using control points. For that, we draw a 1,000 random samples stratified between two classes: mine and no-mine. The control points are also available as a GPKG file, including the variables: MAPPED, REFERENCE, FID with the feature ID, and geom in geographical coordinates WGS84. The overall accuracy calculated from the control points was 88.4%. For other accuracy metrics see the source link.

validation_points_v1.gpkg

**Link:** https://doi.pangaea.de/10.1594/PANGAEA.910894

Always use the following citation when using this data:

Maus, Victor; Giljum, Stefan; Gutschlhofer, Jakob;

**Global-scale mining polygons (Version 2)**

**Location-** Worldwide

**Description-**

This dataset updates the global-scale mining polygons (Version 1) available from https://doi.org/10.1594/ PANGAEA.910894. It contains 44,929 polygon features, covering 101,583 km² of land used by the global mining industry, including large-scale and artisanal and small-scale mining. The polygons cover all ground features related to mining, .e.g open cuts, tailing dams, waste rock dumps, water ponds, processing infrastructure, and other land cover types related to the mining activities. The data was derived using a similar methodology as the first version by visual interpretation of satellite images. The study area was limited to a 10 km buffer around the 34,820 mining coordinates reported in the S&P metals and mining database. We digitalized the mining areas using the 2019 Sentinel-2 cloudless mosaic with 10 m spatial resolution (https:// s2maps.eu by EOX IT Services GmbH - Contains modified Copernicus Sentinel data 2019). We also consulted Google Satellite and Microsoft Bing Imagery, but only as additional information to help identify land cover types linked to the mining activities. The main data set consists of a GeoPackage (GPKG) file, including the following variables: ISO3_CODE, COUNTRY_NAME, AREA in squared kilometres, FID with the feature ID, and geom in geographical coordinates WGS84. The summary of the mining area per country is available in comma-separated values (CSV) file, including the f o l l o w i n g v a r i a b l e s : ISO3_CODE, COUNTRY_NAME, AREA in squared kilometres, and N_FEATURES number of mapped features. Grid data sets with the mining area per cell were derived from the polygons. The grid data is available at 30 arc-second resolution (approximately 1x1 km at the equator), 5 arc-minute (approximately 10x10 km at the equator), and 30 arc-minute resolution (approximately 55x55 km at the equator). We performed an independent validation of the mining data set using control points. For that, we draw 1,000 random samples stratified between two classes: mine and no-mine. The control points are also available as a GPKG file, including the variables: MAPPED, REFERENCE, FID with the feature ID, and geom in geographical coordinates WGS84. The overall accuracy calculated from the control points was 88.3%, Kappa 0.77, F1 score 0.87, producer's accuracy of class mine 78.9 % and user's accuracy of class mine 97.2 %.

**Link-** https://doi.pangaea.de/10.1594/PANGAEA.942325

**Minerals Backbone of Economy - (World Mining Data)**

**Location-** Worldwide

**Description-**

Mineral Raw Materials are mineral constituents of the earth's crust which are of economic value. In the most comprehensive sense this includes the so-called "mine output" as well as the output from processing at or near the mines (for instance, the up-grading of ores to concentrates).

**Tags-** Minerals, Mining, Economy, Natural Resource

**Link-** https://www.world-mining-data.info/?

**World_Mining_Data___Data_Section Mines and Mineral Resources**

**Location-** Multiple

**Description-**

This dataset represents mineral resource mines, excluding sand and gravel quarries. Only mines believed to be operational are included. To enable a first responder or law enforcement team to easily drive to the mine the point representing the mine has been placed at the place where the main "haul road" meets the nearest public road. This location may be a considerable distance from the mine pit or shaft, but from this point on the ground it should be obvious how to drive to the mine itself.

**Type-** Minerals, Mining, Economy, Natural Resource

**Link-** https://data.world/dhs/mines-and-mineral-resources

**Greece Mining Production**

**Location-** Greece

**Description-**

Mining production in Greece increased 6.40 percent in February of 2023 over the same month in the previous year. Mining Production in Greece averaged -2.11 percent from 2001 until 2023, reaching an all time high of 47.90 percent in April of 2021 and a record low of -28.30 percent in January of 2015. This page provides - Greece Mining Production actual values, historical data, forecast, chart, statistics, economic calendar and news.

**Tags-** Minerals, Mining, Economy, Natural Resource, Production

**Link-** https://tradingeconomics.com/greece/miningproduction

**Coal Mining Operation -Post Mining Treatment Facility**

**Location-** Multiple

**Description-** Represents the Primary Facility type Coal Mining Operation (CMO) point features for post mining treatment. Post-mining discharges are groundwater seeps and flows that occur after a mine has been completed and reclaimed. Many of these discharges have become contaminated by contacting acid producing rock in the mine environment. Untreated discharges that enter clean streams cause acidification, which immediately kills much of the aquatic life. Coal mines that are predicted to have discharges are not permitted; however, coal mining operators are required to treat postmining discharges in cases where the predictions do not come true. Through advances in predictive science, less than 2 percent of the permits issued today result in a postmining discharge. New technologies, including alkaline addition and special handling of acid producing material, are being studied in order to help address the remaining 2 percent.

**Tags-** Coal Mining, Treatment, Discharge,

**Link-** np_clip=https://newdata-padep-1.opendata.arcgis.com/maps/f69db0e0c3d3488cb27eb57a6c439396/about

**Mining Leases**

**Location-** Multiple

**Description-**

This dataset contains Mining Leases issued under the Minerals Development Act (Northern Ireland) 1969 by the Department for the Economy. These data geometry are polygons showing the extent of the lease. The attribute table identifies the Lease ID, the Lease Holder, the date the lease was issued and the date the lease is due to expire. These data are provided in the following formats: Geodatabase, GeoJSON, Geopackage, KMZ. GeoJSON and KML data are in Lat Long, WGS84. GeoDatabase, GeoPackage are in Irish National Grid.

**Tags-** Mining, lease,

**Link-** https://www.data.gov.uk/dataset/fbd0c401-a655-478ab730-3ad90cc426e4/mining-leases

**Gross output of total U.S. mining industry 2000-2021**

**Location-** Multiple

**Description-**

In 2021, the gross output of the United States mining industry amounted to 628.5 billion U.S. dollars. That was an increase of more than 212 billion U.S. dollars compared to the previous year. U.S. mining industry: an economic overview of the past two decades. The mining industry in the United States is a huge sector – especially when oil and gas extraction is included. In 2021, the industry generated a gross output of nearly 629 billion U.S. dollars. In 2000, this figure stood at just 218 billion. The value added of the U.S. mining industry was 333.9 billion U.S. dollars in 2021, while this figure was around 81 billion in 1998. In 2000, U.S. mining employment stood at 521,000. It has remained relatively stable since 2000, having grown to a peak of 842,000 in 2014, before decreasing gradually to 539,000 mine employees as of 2020. U.S. mining companies in a global context Although the United States has an active and diverse mining industry, U.S. mining companies are not among the top ten mining companies worldwide based on revenue. Rather, the U.S.-based Freeport McMoRan, ranked 12th among the world's largest mining companies based on revenue as of 2022. Freeport McMoRan was the second leading U.S. mining company based on revenue in 2022 with a revenue of over 24 billion U.S. dollars.

**Tags-** Mining Economy, Mineral, Industry

**Link-** https://www.statista.com/statistics/193416/grossoutput-of-total-us-mining-industry-since-1998/

**Gold and Gold mining Dataset - Atena**

**Location-** Multiple

**Description-** Gold is a rare, noble metal. It does not oxidize and occurs mainly in the elemental form; gold salts are not stable in aqueous solutions but tend to precipitate as elemental gold. In contrast, coordination complexes of gold are stable. Gold has been analyzed in different matrices and at different concentration levels using fire analysis, flame atomic absorption, flameless atomic absorption spectrometry, or inductively coupled plasma mass spectrometry.Levels of environmental and even occupational exposure are low. Measurable exposure can be caused by dental inlays, crowns, and bridges, but even this type of exposure apparently has little toxicological significance. Some thiol compounds of gold have been used in the treatment of rheumatic arthritis. They are rapidly metabolized, those given orally apparently already before absorption. The coordination complex, [Au(CN)2]-, seems to be a common metabolite of all of these drugs.Allergic dermatitis induced by metallic gold is rare, but positive patch tests to gold occur in up to 30% of tested people. Large doses, in the order of several grams as cumulative total dose, have been used in the treatment of rheumatic arthritis parenterally, and the incidence of side effects has been high. The most common effects are related to the skin and mucous membranes; the most serious, even fatal, effect is the suppression of bone marrow. Effects of gold therapy on the kidney are relatively frequent and are usually reversible upon cessation of the therapy. Lung damage induced by gold therapy is rare, and usually reversible, but fatal cases have also been described. Mild gastrointestinal symptoms are very frequent; serious colitis is very rare but may be fatal.In repeated dose studies in experimental animals, the kidney is the main target organ of gold toxicity; at high doses, tubular necrosis, and at lower doses, cortical fibrosis of the kidney has been observed. Such findings have not been reported in exposed humans. Repeated intramuscular (i.m.) administration of gold thiomalate has caused injection site sarcomas in rats. Longterm administration of auranofin and triethylphosphine gold orally or aurothiomalate i.m. caused renal adenomas in rats. High doses of gold were embryotoxic and induced teratogenic effects in rats and rabbits.Large interindividual variation in gold concentrations in the blood and urine, related to leaching of gold from dental appliances makes it impossible to use biological monitoring to assess exposure to gold. While there are some studies indicating an association between therapeutic or adverse effects of gold and concentrations of gold in biological media, the majority of studies have not observed any such association.

**Tags-** Gold, Mining, Mineral

**Link-** https://atena.urv.cat/dataset/5c2973b7-e209-46be-9424-0d52df6e876d

**Russia Mining and Quarrying Volume: Ores & Others: Gold Ores & Concentrates**

**Location-** Russia

**Description-**

Russia Mining and Quarrying Volume: Ores & Others: Gold Ores & Concentrates data was reported at 106.400 Prev Year=100 in 2017. This records an increase from the previous number of 102.600 Prev Year=100 for 2016. Russia Mining and Quarrying Volume: Ores & Others: Gold Ores & Concentrates data is updated yearly, averaging 106.650 Prev Year=100 from Dec 2010 to 2017, with 8 observations. The data reached an all-time high of 110.900 Prev Year=100 in 2013 and a record low of 97.400 Prev Year=100 in 2015. Russia Mining and Quarrying Volume: Ores & Others: Gold Ores & Concentrates data remains active status in CEIC and is reported by Federal State Statistics Service. The data is categorized under Russia Premium Database’s Mining and Quarrying Sector –

**Table RU.BAF001: Mining and Quarrying Volume: Ores and Others: Summary.**

**Tags-** Mining, Quarrying, Mineral Ore,

**Link-** https://www.ceicdata.com/en/russia/mining-andquarrying- volume-ores-and-others-summary/mining-andquarrying- volume-ores--others-gold-ores--concentrates

**Mining in Morocco Field Value Source minerals.usgs.gov**

Last Updated 25. Oktober 2016, 11:54 (UTC+02:00) Erstellt 25. Oktober 2016, 11:39 (UTC+02:00)

**Link-** https://open.africa/de/dataset/mining-in-morocco

**Geological Image Similarity**

**Location-** Russia

**Description**-

A geology research company wants to create a tool for identifying interesting patterns in their imagery data. This tool will possess a search capability whereby an analyst provides an image of interest and is presented with other images which are similar to it. Task is to create the machine learning component for this image similarity application. The machine learning model should return the top K images that are most similar to this image based on a single image input.

**Tags-** Geology, Minerals, Rock, Rock

**Link-** https://www.kaggle.com/datasets/tanyadayanand/geological-image-similarity?select=geological_similarity

**Rock Image Dataset** 

**Location-** Multiple

**Description-**

This dataset is prepared by a team of Brac University Mars Rover Team for the purpose of research of similar rocks identification in a mars-like surface. The dataset contains three different types of rocks such as - Igneous, Metamorphic, sedimentary, etc.

**Tags-** Rock Image, Geology, Exploration

**Link-** https://data.mendeley.com/datasets/7g7zpy9vcb

**CLM - Geology and Petroleum potential image**

**Location-** Multiple

**Description-**

This dataset was supplied to the Bioregional Assessment Programme by a third party and is presented here as originally supplied. The metadata was not provided by the data supplier and has been compiled by the programme based on known details.\n\n\n\nThis is a scanned image of a geological map which is part of the publication by Wells and O'Brien (1994). It shows the geology of the Clarence- Moreton Basin.\n\n\n\nWells, AT and O'Brien, PE (compilers and editors) (1994a) Geology and petroleum potential of the Clarence-Moreton Basin, New South Wales and Queensland. Australian Geological Survey Organisation, Bulletin 241. Australian Geological Survey Organisation, Canberra.

Dataset History \n\nThis is a scanned image of a geological map which is part of the publication by Wells and O'Brien (1994). It shows the geology of the Clarence-Moreton Basin.\n\n\n\nIt was geo-referenced using Global Mapper software.\n\n\n\nReference: Wells, AT and O'Brien, PE (compilers and editors) (1994a) Geology and petroleum potential of the Clarence-Moreton Basin, New South Wales and Queensland. Australian Geological Survey Organisation, Bulletin 241. Australian Geological Survey Organisation, Canberra.

Dataset Citation \n\nAustralian Geological Survey Organisation (2015) CLM - Geology and Petroleum potential image. Bioregional Assessment Source Dataset. Viewed 28 September 2017.

**Tags-** Geology, Petroleum, Well-log

**Link-** http://data.bioregionalassessments.gov.au/dataset/3b5b0b66-d0fb-4b79-a0c1-5cd3719b44fc.

**The GeoScour Open dataset**

**Location-** Multiple

**Description-**

The BGS GeoScour Open datasets provide a generalised overview of the natural characteristics and properties of catchment and riverine environments for the assessment of river scour in Great Britain. The GeoScour Open dataset comprises two different tiers of geographical information system data containing seven different data layers. Each tier represents a different scale of assessment, from a high-level catchment to subcatchment data. The datasets are polygon (area) layers, which are described using straightforward classifications and enabling an indicative catchment susceptibility assessment.

**Tags-** Geology, Geography, River, Natural

**Link-** https://www.bgs.ac.uk/download/bgs-geoscour-open-2/

**Minerals Identification Dataset**

**Location-** Multiple

**Description-**

Identification of minerals in the field is a task that is wrought with many challenges. Traditional approaches require expertise and are prone to errors. Deep learning methods can help overcome some of these hurdles to provide simple and effective ways to identify minerals. However, existing techniques mainly make use of features of the minerals under a microscope and tend to favour a manual feature extraction pipeline.

**Tags-** Minerals, Rock, Geology, Sedimentology

**Link-** https://www.kaggle.com/datasets/asiedubrempong/minerals-identification-dataset

**Mineral export records 2015-2018**

**Location-** Multiple

**Description-**

To provide an enabling environment for the socioeconomic development of the Solomon Islands through the application of necessary safeguards with regard to:sustainable use of natural resources, the provision of meteorological services, reducing the risk and impact of climate change and other hazards to communities, leading and managing disaster preparedness and their consequences. The MECDM has 4 Divisions and 1 Office which include: Climate Change Division (CCD), Corporate Services Division, Environment & Conservation Division (ECD), Meteorological Services Division, National Disaster Management Office (NDMO)

**Link-** https://solomonislands-data.sprep.org/dataset/mineral-export-records-2015-2018

**Dataset for mineral resource inventory of North Dakota**

**Location-** North Dakota, USA

**Description-**

This data release contains the geospatial resources that were used by the USGS to compile the mineral resource inventory for the state of North Dakota, developed by the Mineral Resource Program (MRP) staff of the U.S. Geological Survey (USGS) at the request of the Bureau of Land Management (BLM). The mineral resources inventory was published as a USGS open-file report and can be accessed at https://doi.org/10.3133/ofr20211057. Commodities considered under this inventory include Critical Minerals as listed in the Federal Register (May 18, 2018), along with sodium sulfate, frac or proppant sand, bentonite and ceramic-grade kaolinite. Other selected leasable and salable mineral commodities were also inventoried, based on information provided to the USGS by BLM. This data release includes published GIS data and their accompanying original metadata, along with GIS data sourced from publications that was created for use with this minerals inventory investigation. The following numbered folders are included: “1_Georeferenced_TIFs”: georeferenced images used for locating, identifying and creating vector data representing those mineral assets that were herein inventoried; “2_Minerals_databases”: national mineral databases available in digital format, LR2000, MRDS, USMIN—North Dakota-related data, and NDAML (North Dakota Abandoned Mine Land); “3_NDGISHUB”: a digital geologic map of North Dakota, and “4_Feature_ classes”: feature classes digitized by the authors and used to visually represent the distribution of the mineral assets being inventoried. Note that the feature classes in the “4_Feature_ classes” folder do not contain individual metadata files - all descriptive information for them can be found in the "ND_metadata.xml" metadata file.

**Tags-** Mineral Resource,

**Link-** https://www.sciencebase.gov/catalog/item/6198231ed34eb622f692ef5e

**Location-** Russia

**Description-**

This report presents data, including latitude and longitude, for aggregate sites in New Mexico that were believed to be active in the period 1997-1999. The data are presented in paper form in Part A of this report and as Microsoft Excel 97 and Data Interchange Format (DIF) files in Part B. The work was undertaken as part of the effort to update information for the National Atlas. This compilation includes data from: the files of U.S. Geological Survey (USGS); company contacts; the New Mexico Bureau of Mines and Mineral Resources, New Mexico Bureau of Mine Inspection, and the Mining and Minerals Division of the New Mexico Energy, Minerals and Natural Resources Department (Hatton and others, 1998); the Bureau of Land Management Information; and direct communications with some of the aggregate operators. Additional information on most of the sites is available in Hatton and others (1998).

**Link-** https://pubs.usgs.gov/of/2000/0011/

**Geologic map of Alaska** 

**Location-** Alaska

**Description-** Digital compilation and reinterpretation of published and unpublished geologic mapping of Alaska. This information was published by USGS as Scientific Investigations Map 3340.

**Tags-** Geology, Maps,

**Link-** https://mrdata.usgs.gov/sim3340/

**Mined Land Permits:Beginning 1974**

**Location-** Multiple

**Description-** This coverage contains data from the Division of Mineral Resources Mined Lands permit files. This coverage contains data from the Division of Mineral Resources Mined Lands permit files.

**Source:** https://data.ny.gov/d/va8e-9s3h

Last updated at https://data.ny.gov/data.json : 2020-05-14 Before using the data, download the Terms of Service,

https://data.ny.gov/download/77gx-ii52/application/pdf, to read the data license requirements.

**Tags-** minerals, gravel, stone, aggregate, mines, mined land, energy environment

**Link-** https://data.world/data-ny-gov/va8e-9s3h

**Mines in Africa-**

**Location-** Multiple

**Description-** Number of mineral mines (total and by commodity) for 5,835 African ADM2 units. This is a cross-sectional dataset with information about the number of mineral mines (total and by commodity) for 5,835 African ADM2 units. The table contains the total number of mines and total number of mines by 24 commodities for each ADM2 district in Africa.The raw data was sourced from the U.S. Geological Survey (USGS) 2005. Mineral Resources Data System.

**Tags-** mines, minerals, resources, Africa

**Link:** http://datainspace.org/index.php/mines-in-africa/

**Mineral Resources Data System**

**Location-** Multiple

**Description-** Mineral resource occurrence data covering the world, most thoroughly within the U.S. This database contains the records previously provided in the Mineral Resource Data System (MRDS) of USGS and the Mineral Availability System/Mineral Industry Locator System (MAS/MILS) originated in the U.S. Bureau of Mines, which is now part of USGS. The MRDS is a large and complex relational database developed over several decades by hundreds of researchers and reporters. This product is a digest in which the fields chosen are those most likely to contain valid information.

Data Provided By: U.S. Geological Survey

Content date: 20120127

Citation: http://mrdata.usgs.gov/mrds/ http://mrdata.usgs.gov/services/mrds? request=getcapabilities&service;=WMS&version;=1.1.1 http://mrdata.usgs.gov/services/mrds? request=getcapabilities&service;=WFS&version;=1.0.0 Contact Organization: USGS ER GD Contact Person(s): Peter N. Schweitzer Use Const

**Link-** https://databasin.org/datasets/4b77ce7e8eae4480afc15003f4c71c2b/

**Construction Minerals Location-**

**Description-** This dataset represents construction minerals operations in the United States. The data represent commodities covered by the Minerals Information Team (MIT) of the U.S. Geological Survey. The mineral operations are plants and (or) mines surveyed by the MIT and considered currently active in 2003. Excluded are construction sand and gravel and crushed stone. These data are intended for geographic display and analysis at the national level, and for large regional areas. The data should be displayed and analyzed at scales appropriate for 1:2,000,000-scale data.

**Tags-** mining, opportunity, minerals, homeland security,opportunity homeland security

**Link-** https://data.world/dhs/construction-minerals

Ferrous Metal Mines Location-

Description- This dataset represents ferrous metal mines in the United States. The data represent commodities covered by the Minerals Information Team (MIT) of the U.S. Geological Survey, and the operations are those considered active in 2003 and surveyed by the MIT. These data are intended for geographic display and analysis at the national level, and for large regional areas. The data should be displayed and analyzed at scales appropriate for 1:2,000,000-scale data.

TAGS- mining, opportunity, homeland security, minerals, opportunity homeland security Link- https://data.world/dhs/ferrous-metal-mines

GSI Bedrock Symbols 100K

**Location- ** Russia

Description- This data represents a seamless bedrock geological dataset encompassing Republic of Ireland and parts of Northern Ireland. The seamless geological dataset was created from the GSI Bedrock 1:100,000 scale digital geological map series. The dataset comprises 6 key shape files.

1) Bed100k.shp -

A polygon shapefile that contains bedrock geological information on Stratigraphy, Igneous, Lithology and Diagentic codes, their unitnames and brief descriptions. Fields: AREA: Area of the polygon in square metres. Field type: Double. PERIMETER: Perimeter of polygons in metres: Field type: Double. NEWCODE: unique identifier for every formation or member. Field type: String. SHEETNO: 100k sheets from which they originated before creating the seamless version. Field type: Double. STRATCODE: Stratigraphic code for unit, as labeled on printed maps and their legends. Field type: String. LITHCODE: Lithological code. Field type: String. DESCRIPT: Brief description of the dominant rock types. Field type: String. C,M,Y,K: cyan, magenta, yellow and black percentage. Field types: Double. UNITNAME: Name of the geological formation or member. Field Type: String.

3) Index100k.shp - An overlay polygon index of 1:100,000 scale printed map sheets. Fields: SHEETNO: 1:100,000 printed sheet number. Field type: Double.

4) Struc100k.shp (Structural Linework) -

A linework shapefile that contains structural geological linework codes and descriptions Fields: LENGTH: Length of the feature in metres: Field type: Float. CODE: Unique identifier for structure type. Field type: String. SHEET: The 1:100,000 printed map sheet number on which the structure was originally located. Field type: Double. FOLDNAME: Name field for regionally important folds. Field type: String. FAULTNAME: Name field for regionally important faults. Field type: String. ADDITION: Additional information field for structure. Field type: String. DESCRIPT: Description of structure type. Field type: String. SLIDE: Name field for regionally important slides. Field type: String.

7) Strat10igraphic Linework) -

A linework shapefile that contains stratigraphic geological line codes and descriptions. Fields: LENGTH: Length of the feature in metres: Field type: Float. CODE: Unique identifier for stratigraphic line type. Field type: String. SHEET: The 1:100,000 printed map sheet number on which the stratigraphic line was originally located. Field type: Double. DESCRIPT: Description of stratigraphic line type. Field type: String. ADDITION: Additional information field for stratigraphic line. Field type: String. DYKELABEL: Igneous dyke code identifier. Field type: String. STRATCODE: Stratigraphic code for narrow formations or members which are represented by a line rather than a polygon in Bed100k. Field type: String. LITHCODE: Lithological code for narrow formations or members which are represented by a line rather than a polygon in Bed100k. Field type: String.

10) NZL_GNS_GM6_Victoria_ Range

Location- New Zealand

Description- The Geology of the Victoria Range area (NZL_GNS_GM6_geology) comprises a 1:50 000 geological dataset covering part of the Buller District on the West Coast of the South Island of New Zealand. Source: https://catalogue.data.govt.nz/dataset/ nzl_gns_gm6_victoria_range Last updated at https://catalogue.data.govt.nz/organization/ gns-science : 2020-09-10 License - Creative Commons Attribution 3.0 New Zealand (CC BY 3.0 NZ)

TAGS buller district, new zealand, west coast, geology, geophysics, igneous petrology, minerals

Link- https://data.world/nz-gns-science/0f28dd6d-2af2-4267-9ee7-1f3c7fe9cc79

Glass Buttes Well 52-33Core Log

Location- Multiple Description- Core log from Glass Buttes Well 52-33, drilled by Geodrill Rig 6 in 2014 to a depth of 3000 feet. Logged at 500 ft intervals.

Source: https://catalog.data.gov/dataset/glass-butteswell- 52-33-core-log-5cfce

Last updated at https://catalog.data.gov/organization/doe-

Tags- fractures, geothermal, lithology, minerals, minerology, oregon, temperature

LICENSE CC-BY DICTIONARY

1 file, 0 columns, 0 tables·View

Map based index (GeoIndex) mineral occurrences

Location- UK

Description- This layer of the map based index (GeoIndex) shows the locations of known mines, mineral showings and localities, including sites where minerals of economic interest have been identified in panned concentrates. The information for the index is taken from the Mineral Occurrence Database. The Mineral Occurrence Database holds information on mineral occurrences in the UK including locations of known mines, deposits, prospects and mineral showings, including sites where minerals of potential economic interest have been identified in panned concentrates. Data is normally taken from published sources or from internal BGS records, such as field sheets, rock and stream sediment collection cards. Data compilation started ca. 1994 and the database currently holds about 13 000 records, but details of many more old workings and occurrences remain to be added.

Tags: Mineral, Geology, Deposits,

Source: https://ckan.publishing.service.gov.uk/dataset/mapbased- index-geoindex-mineral-occurrences1

Last updated at https://ckan.publishing.service.gov.uk/

dataset : 2022-06-15

**Location-

Description-** This data represents a seamless bedrock geological dataset encompassing Republic of Ireland and parts of Northern Ireland. The seamless geological dataset was created from the GSI Bedrock 1:100,000 scale digital geological map series. The dataset comprises 6 key shape files. Link- https://data.world/geological-surv/ 700b93ce-23c3-4f0d-a7ac-ad0e551a5f79 GSI Bedrock Stratigraphic Linework 100k

Ferrous Metal Processing Plant

Location-

Description-

This dataset represents ferrous metal processing plants in the United States. The data represent commodities covered by the Minerals Information Team (MIT) of the U.S. Geological Survey, and the operations are those considered active in 2003 and surveyed by the MIT. These data are intended for geographic display and analysis at the national level, and for large regional areas. The data should be displayed and analyzed at scales appropriate for 1:2,000,000-scale data.

Tags- Ferrous, Metal, Mineral, Plant, Production

Link- https://data.world/dhs/ferrous-metal-processing-plant

Total Sediment Thickness of the World's Oceans and Marginal Seas

Location-

Description- CEI's global ocean sediment thickness grid of Divins (2003) updated by Whittaker et al. (2013) has been updated again for the NE Atlantic, Arctic, Southern Ocean, and Mediterranean regions. The new global 5‐arc‐minute total sediment thickness grid, GlobSed, incorporates new data and several regional oceanic sediment thickness maps, which have been compiled and published for the, (1) NE Atlantic (Funck et al., 2017; Hopper et al., 2014), (2) Mediterranean (Molinari & Morelli, 2011), (3) Arctic (Petrov et al., 2016), (4) Weddell Sea (Huang et al., 2014), and (5) the Ross Sea, Amundsen Sea, and Bellingshausen Sea sectors off West Antarctica (Lindeque et al., 2016; Wobbe et al., 2014). This version also includes updates in the White Sea region based on the VSEGEI map of Orlov and Fedorov (2001). GlobSed covers a larger area than NCEI’s previous global grids (Divins, 2003; Whittaker et al. 2013), and the new updates results in a 29.7% increase in estimated total oceanic sediment volume.

Tags-

Link- https://www.ngdc.noaa.gov/mgg/sedthick/

Geospatial database of the 2018 lower East Rift Zone eruption of Kīlauea Volcano, Hawaiʻi

Location-

Description- The 2018 lower East Rift Zone eruption of Kīlauea Volcano began in the late afternoon of 3 May, with fissure 1 opening and erupting lava onto Mohala Street in the Leilani Estates subdivision, part of the lower Puna District of the Island of Hawaiʻi. For the first week of the eruption, relatively viscous lava flowed only within a kilometer (0.6 miles) of the fissures within Leilani Estates, before activity shifted downrift (eastnortheast) and out of the subdivision during mid-May. Around 18 May, activity along the lower East Rift Zone intensified, and fluid lava erupting at higher effusion rates from the downrift fissures reached the ocean within two days. Near the end of May, this more vigorous activity shifted back uprift into Leilani Estates, where fissure 8 reactivated with lava fountains feeding several ʻaʻā flows. The southernmost flow lobe developed into a well-defined lava channel and reached the ocean at Kapoho Bay—11 kilometers (7 miles) away—on 3 June. Fissure 8 continued supplying this lava channel for more than two months, constructing an approximately 3.5- square-kilometer (1.4-square-mile) lava delta along the coastline. Over 4 and 5 August, activity at fissure 8 waned and flow in the lava channel came to a halt, only to be followed by weak activity within the vent in late August and early September. By then, the eruption had covered 35.5 square kilometers (13.7 square miles) of the lower Puna District with lava. In this report, the authors have sought to chronicle this sequence of events using geospatial data in the form of an Esri file geodatabase, Esri shapefiles, and Google Earth KMZs.

Tags- Map ServiceOGC WFS LayerOGC WMS LayerOGC

WMS ServiceShapefile

**Link- **- https://www.sciencebase.gov/catalog/item/5eba3f6082ce25b5135d5b85

Location- Multiple

Description- Multi class classification using different types of images of rocks. This dataset is prepared by a team of Brac University Mars Rover Team for the purpose of research of similar rocks identification in a mars-like surface.

Tags- It contains images of rocks of different types. You will find images of different types of rocks such as - Igneous, Metamorphic, sedimentary, etc

Link- https://www.kaggle.com/datasets/salmaneunus/rock-classification?select=Dataset

Rock Classification Dataset

Description- Marine Geologic data compilations and reports in the NCEI archive are from academic and government sources around the world. Over ten terabytes of analyses, descriptions, and images of sediment and rock from the ocean floor and lakebeds are available. Examples of data available include sediment/rock composition, physical properties, petrology/mineralogy, geochemistry, paleontology, paleomagnetism, x-rays, photographs, and other imagery. All reports and data, regardless of format, are accessible via the Marine Geology Digital Inventory and/or linked to the Index to Marine and Lacustrine Geological Samples (IMLGS). Searches offer free, immediate download of digital data, many images, and .PDF reports, and information on how to obtain fullresolution images from the archive, and order CD-ROMs, microfilm, or oversize charts. Some larger data sets, including the IMLGS, have their own web interfaces. The IMLGS provides searches of sea floor and lakebed cores, grabs, dredges, and drill samples available from sample repositories at partner institutions, with links to browse and download related information from NCEI and other sources.

Tags- Palaeontology, Rock, Sediment, Geology, Mineralogy, petrology/mineralogy, geochemistry, paleontology, paleomagnetism

Location- Multiple

Description- Geo Fossils-I is a synthetic image dataset used as a solution for resolving the limited availability of geological datasets intended for image classification and object detection on 2D images of geological outcrops. The Geo Fossils-I dataset was created to train a custom image classification model for geological fossil identification and inspire additional work in generating synthetic geological data with Stable Diffusion models. The Geo Fossils-I dataset was generated through a custom training process and the fine-tuning of a pre-trained Stable Diffusion model. Stable Diffusion is an advanced textto- image model that can create highly realistic images based on textual input. An effective technique for instructing Stable Diffusion on novel concepts is the application of Dreambooth, a specialized form of fine-tuning. Dreambooth was used to generate new images of fossils or to modify existing ones per the provided textual description. The Geo Fossils-I dataset contains six different fossil types present in geological outcrops, each one being characteristic of a particular depositional environment. The dataset contains a total of 1200 fossil images equally spread among different fossil types such as ammonites, belemnites, corals, crinoids, leaf fossils, and trilobites. This dataset is the first set within a series to be compiled aiming to enrich the available resources with respect to 2D outcrop images allowing geoscientists to progress in the field of automated interpretation of depositional environments.

**Link- ** https://www.kaggle.com/datasets/naifislam/geo-fossil-1

Geo Fossil 1

Location- Multiple

Description- The NSIDC DAAC Advanced Microwave Scanning Radiometer Unified (AMSR Unified) collection includes passive microwave data products on snow, sea ice, soil moisture, vegetation water content, and brightness temperature. The AMSR-U collection has been designed to incorporate data from the Advanced Microwave Scanning Radiometer - Earth Observing System Sensor (AMSR-E) sensor and the Advanced Microwave Scanning Radiometer2 (AMSR2) sensor. From 2002 to 2011, AMSR-E flew onboard NASA's Aqua satellite, collecting passive microwave measurements of land and ocean parameters related to global water and energy cycles. You can learn more about the AMSR-E instrument by visiting the NSIDC DAAC AMSR-E collection. AMSR2 has operated since 2012 onboard the Global Change Observation Mission 1st - Water "SHIZUKU" (GCOM-W1) satellite. The GCOM-W1 mission aims to establish a global, long-term observation system to improve understanding of the mechanisms of climate and water cycle variations. AMSR2 measures microwave emissions from the Earth's surface and atmosphere. It collects both daytime and nighttime observations of Earth, observing more than 99 percent of the planet every two days. For more information about AMSR2, refer to the About AMSR2 - Observing System on the GCOM-W1 website. As a follow-on instrument to AMSR-E, AMSR2 offers enhanced spatial resolution, better calibration, and improved mitigation of radio-frequency interference. Because AMSR2 has been designed as a follow-on mission to AMSR-E, it makes observations that are spatially consistent, easily continuing the data record. Combining reprocessed AMSR-E data with subsequent AMSR2 observations provides a nearly continuous record dating back to 2002. As new data products become available, they are added to the collection. The NSIDC DAAC distributes daily, weekly, and monthly Level-2B and Level-3 AMSR Unified products.The NSIDC DAAC also hosts two other data collections derived from other AMSR sensors that have flown aboard polar-orbiting satellites making global observations. The other collections include: The AMSR-E data collection comes from the AMSR-E sensor that flew onboard NASA’s Aqua satellite, observing interactions between snow and ice, and Earth's atmosphere and ocean. AMSR Unified AMSR Unified - Advanced Microwave Scanning Radiometers PROBING SHALLOW AQUIFERS IN HYPERARID DUNE FIELDS USING VHF SOUNDING RADAR: RAW GROUNDPENETRATING

RADAR (GPR) DATA

Location-

Description- The recent interest in using deep learning for seismic interpretation tasks, such as facies classification, has been facing a significant obstacle, namely the absence of large publicly available annotated datasets for training and testing models. As a result, researchers have often resorted to annotating their own training and testing data. However, different researchers may annotate different classes, or use different train and test splits. In addition, it is common for papers that apply deep learning for facies classification to not contain quantitative results, and rather rely solely on visual inspection of the results. All of these practices have lead to subjective results and have greatly hindered the ability to compare different machine learning models against each other and understand the advantages and disadvantages of each approach. To address these issues, we open-source an accurate 3D geological model of the Netherlands F3 Block. This geological model is based on both well log data and 3D seismic data and is grounded on the careful study of the geology of the region. Furthermore, we propose two baseline models for facies classification based on deconvolution networks and make their codes publicly available. Finally, we propose a scheme for evaluating different models on this dataset, and we share the results of our baseline models. In addition to making the dataset and the code publicly available, this work can help advance research in this area and create an objective benchmark for comparing the results of different machine learning approaches for facies classification for researchers to use in the future.

**Tags: **Computer Vision Machine Learning Geoscience and Remote Sensing, seismic, facies, classification, F3 Block

Link- https://ieee-dataport.org/open-access/facies-markmachine-learning-benchmark-facies-classification

National Geochemical Database: Rock

Location- Description- National Geochemical Database: Rock Geochemical analysis of rock samples collected and analyzed by the USGS. This dataset includes and supersedes rock data formerly released as "Geochemistry of igneous rocks in the US extracted from the PLUTO database". The database contains 414,304 records

Link- https://mrdata.usgs.gov/ngdb/rock/

Utah FORGE: Rock Properties

Location- Utah, USA

Description- This is an Excel spreadsheet that contains rock properties from several wells in the Utah FORGE study area. This includes a map of the wells. Data is described in the Final Topical Report included in the resources below.

Link- https:catalog.data.gov/dataset/utah-forge-rock-properties Last updated at https://catalog.data.gov/organization/doegov : 2021-07-17

Tags- caliper, core, density, egs, energy, forge, gamma, geomechanics, geothermal, kspar, mafics, milford, porosity, properties, quartz, resistivity, resource, rock,

LICENSE CC-BY DICTIONARY

2 files, 380 columns, 0 tables·View

Link- https://mrdata.usgs.gov/ngdb/rock/

GSI Bedrock Stratigraphic Linework 100k

Location- Multiple

Description- This data represents a seamless bedrock geological dataset encompassing Republic of Ireland and parts of Northern Ireland. The seamless geological dataset was created from the GSI Bedrock 1:100,000 scale digital geological map series. The dataset comprises 6 key shape files.

Bed100k.shp - A polygon shapefile that contains bedrock geological information on Stratigraphy, Igneous, Lithology and Diagenetic codes, their unit names and brief descriptions. Fields: AREA: Area of the polygon in square meters. Field type: Double. PERIMETER: Perimeter of polygons in meters: Field type: Double. NEWCODE: unique identifier for every formation or member. Field type: String. SHEETNO: 100k sheets from which they originated before creating the seamless version. Field type: Double. STRATCODE: Stratigraphic code for unit, as labeled on printed maps and their legends. Field type: String. LITHCODE: Lithological code. Field type: String. DESCRIPT: Brief description of the dominant rock types. Field type: String. C,M,Y,K: cyan, magenta, yellow and black percentage. Field types: Double. UNITNAME: Name of the geological formation or member. Field Type: String.

Index100k.shp - An overlay polygon index of 1:100,000 scale printed map sheets. Fields: SHEETNO: 1:100,000 printed sheet number. Field type: Double.

Struc100k.shp (Structural Linework) - A linework shapefile that contains structural geological linework codes and descriptions Fields: LENGTH: Length of the feature in metres: Field type: Float. CODE: Unique identifier for structure type. Field type: String. SHEET: The 1:100,000 printed map sheet number on which the structure was originally located. Field type: Double. FOLDNAME: Name field for regionally important folds. Field type: String. FAULTNAME: Name field for regionally important faults. Field type: String. ADDITION: Additional information field for structure. Field type: String. DESCRIPT: Description of structure type. Field type: String. SLIDE: Name field for regionally important slides. Field type: String.

Strat100k.shp (Stratigraphic Linework) - A linework shapefile that contains stratigraphic geological line codes and descriptions. Fields: LENGTH: Length of the feature in metres: Field type: Float. CODE: Unique identifier for stratigraphic line type. Field type: String. SHEET: The 1:100,000 printed map sheet number on which the stratigraphic line was originally located. Field type: Double. DESCRIPT: Description of stratigraphic line type. Field type: String. ADDITION: Additional information field for stratigraphic line. Field type: String. DYKELABEL: Igneous dyke code identifier. Field type: String. STRATCODE: Stratigraphic code for narrow formations or members which are represented by a line rather than a polygon in Bed100k. Field type: String. LITHCODE: Lithological code for narrow formations or members which are represented by a line rather than a polygon in Bed100k. Field type: String.

5) EasyGSH-DB

Sedimentology Dataset

Location- Multiple

Description- All data sets for sedimentology have on-the-fly generated preview images, metadata and data sets, click on desired format to download.

Select year: Web services for geographic information systems: WMS - https://mdi-dienste.baw.de/geoserver/ EasyGSH_Sediment/wms WFS - https://mdi-dienste.baw.de/geoserver/ EasyGSH_Sediment/wfs WCS - https://mdi-dienste.baw.de/geoserver/ EasyGSH_Sediment/wcs

Seismic dataset Location- Multiple

Description- The original Seismic dataset from UCI machine learning repository is a binary classification dataset having 19 attributes. It is an unbalanced dataset where the positive (hazard) class is a minority class and considered as outlier class and the negative class (no hazard) is considered as inlier class. Out of 19 attributes 11 are utilized for outlier detection.

Tags-Local Density meets Spectral Outlier Detection.

Link- http://odds.cs.stonybrook.edu/seismic-dataset/

Seismic Time-Series Dataset

Location- Multiple

Description- The IRIS DMC archives time series (waveform) data from stations around the world. Passive Source data is collected continuously, and usually monitors natural seismic activity. Often, known events are used to identify segments of data to fetch. Active Source data usually involves the creation of seismic events using explosives or mechanical devices like air guns. Discrete data sets may be collected and organized around these events. This is the primary IRIS archive, containing primarily passive source data in SEED format. Data channels are organized by FDSN identifier elements, and primarily accessed through a data service API. Assembled data primarily comes from temporary deployments and in formats other than SEED. Data comes from various sources including IRIS PASSCAL (mostly active source), the USGS, and others.

Tags-

Link- https://ds.iris.edu/ds/nodes/dmc/data/types/timeseries-data/

Seismic Event Data

**Location- ** Multiple

Description- RIS aggregates event data from a number of independently-operated catalogs. ISF format with DMC extensions WEED Summary File Format Event Search Tools All Event Tools Wilber IEB – IRIS Earthquake Browser PyWEED Tags

Earthquakes Event Web Service

Link- https://ds.iris.edu/ds/nodes/dmc/data/types/events/

Earthquake Archives Location- Multiple

Description- The old seismograms, if properly interpreted, provide invaluable information on earthquakes in the past, and every effort should be made to save them, regardless of their quality, from possible loss and to make copies in an easily readable form." Hiroo Kanamori (1988). I. Introduction The purpose of these International Digital Earthquake Archives (IDEAs) is to preserve earthquake data, specially seismograms, for future research. For example, Hiroo Kanamori used seismograms recorded at Debilt, the Netherlands to demonstrate that the 1960 Chile and the 1964 Alaskan earthquakes are indeed "Great Earthquakes", much larger than other "great earthquakes", such as, 1952 Kamchatka and 1963 Kurile earthquakes, 1923 Kanto and 1924 Mindanao, 2001 Peru, and 2001 Peru. Seismograms, data, and related materials of selected earthquakes are stored in archives as computer data files so that they are freely accessible via the Internet, and seismograms (in originally scanned resolution) are downloadable from the IRIS Data Management Center. Volunteers and donors are welcome. Please contact William H.K. Lee.

II. International Digital Earthquake Archives

1906 San Francisco Earthquake Archive dedicated to Prof. A.C. Lawson and Prof. H.F. Reid 1906 Aleutian Is. Earthquake Archive in Memory of Prof. Donald B. Scott. 1906 Valparaiso (Chile) Earthquake Archive in Memory of Prof. Donald B. Scott 1909 Taipei (Taiwan) Earthquake Archive in Memory of Prof. Ta-You Wu 1920 Haiyuan, Ningxia Province, Republic of China August 14, 1939 Cuban Earthquake Archive July 29, 1943 Puerto Rico Earthquake Archive July 30, 1943 Puerto Rico Earthquake Archive August 4, 1946 Hispaniola Earthquake Archive August 8, 1946 Hispaniola Earthquake Archive October 4, 1946 Hispaniola Earthquake Archive April 21, 1948 Hispaniola Earthquake Archive June 28, 1948 Fukui (Japan) Earthquake Archive in Memory of Prof. Masayuki Kikuchi May 31, 1953 Hispaniola Earthquake Archive 1957 Daly City (California) Earthquake Archive in Memory of Mr. Manuel G. "Doc" Bonilla (in preparation) 1960 Great Chilean Earthquake Archive in Honor of Prof. Hiroo Kanamori (in preparation) 1962 Qazvin (Iran) Earthquake Archive Archives by Stations

**Location- **Multiple

Description- These archives contain seismograms and related materials of the "Reference Stations of the World". These Reference Stations are chosen for their strategic locations and long durations in operation. Volunteers are welcome. Please contact William H.K. Lee at: whklee@usgs.gov For this project, we hope to have several types of information added to the site. They include: bulletins of seismic stations, early-20th-century lists of seismic stations (1921, 1931, 1953, 1964, and 1979), inventories of data holdings of paper seismograms at the Denver Federal center in Lakewood, Colorado, the USGS microfilm holdings in Golden, Colorado, TIFF images of seismograms of Caribbean earthquakes and several years of the reference stations. Finally, we have more than 4,000 images of Tide gauge records (marigrams) of tsunami copied from the DVD holdings of the NGDC in Boulder, Colorado. (Bill McCann, March 31, 2009; Mike Diggles, December 9, 2009) Each seismogram on microfilm was scanned at 8-bit gray scale and high resolution (2400 dpi or better, so that it is equivalent to 300 dpi or better for the original-size seismogram before microfilming) and image editing was performed for quality control.

Puerto Rico Archives by Stations— Puerto Rico

Location- Puerto Rico

Description- A seismographic station in Puerto Rico has been in operation as Vieques (VQS) from 1903-1924, as San Juan (SJP) from 1926-1963, and San Juan (SJG) from 1963 to the present. A history of seismic recording in Puerto Rico is given in the file seismic- recording_history_Puerto_Rico (folder). This folder contains three related files: seismic-recording_history_Puerto_Rico.pdf paper_and_microfilm_inventory_for_IRIS.xls paper_and_microfilm_inventory_for_IRIS_table_notes.pdf For SJP, the station information is given in the files San_Juan_Charlier_1953.pdf and San_Juan_McComb_and_West_1931.pdf. For VQS, a brief 1921 station summary is given in the file: Vieques_Wood_1921.pdf For VQS, the 1903-1904 station information is given in the file: Vieques_1903-1924.pdf Seismogram Images Index of scanned seismogram image files of the World- Wide Standardized Seismograph Network (WWSSN) that are ready for download The following links go to tens of gigabytes of scanned seismograms. There is one link per station folder (e.g., SJG_Cayey). Each station folder contains one or more folders for years (e.g., SJG_1968). Where warranted, the year folders are further divided into month folders (e.g., SJG_1968-03). Each folder may contain several hundred seismogram scan files. In each case, there is both a small "thumbnail" (JPG or GIF) of the seismogram and the large compressed file (.zip, .gz, or max-quality (12) .jpg) of the scan itself. These latter files are each up to 50 MB in size. SJG_Cayey (folder). The filenames for SJG begin with month, day, and year (e.g., 030168 is March 1st, 1968). The filenames end with _01 through _06 to indicate the component of the seismogram as follows: _01, LP Vertical-component; _02, LP NS-component; _03, LP EW-component; _04, SP Vertical-component; _05, SP NS-component; _06, SP EW-component. View a PDF of a table of example filenames for March 1968. SJP_San_Juan (folder). Each original seismogram of SJP was scanned at 8-bit gray scale with a resolution of 500 dpi and image editing was performed for quality control. The filenames for SJP

Location- Multiple

Description- STEAD includes two main classes of earthquake and nonearthquake signals recorded by seismic instruments. At this stage, the earthquake class contains only one category of local earthquakes with about 1,050,000 three-component seismograms (each 1 minute long) associated with ~ 450,000 earthquakes (Fig. 3) that occurred between January 1984 and August 2018. The earthquakes in the data set were recorded by 2,613 receivers (seismometers) (Fig. 7) worldwide located at local distances (within 350 km of the earthquakes). The non-earthquake class currently contains only one category of seismic noise including ~100,000 samples. Locations of instruments recording noise waveforms are presented in Fig. 5. Most of the seismograms have been recorded since 2000 (Fig. 6) in the United States and Europe where denser station coverage is available.

Tags- Earthquake, Seismic, Global, Seismometer

Link- https://github.com/smousavi05/STEAD

STanford EArthquake Dataset (STEAD):A Global Data Set of Seismic Signals for AI

Kimama Well - Borehole Geophysics Database

Location- Multiple

Description- The Snake River Plain (SRP), Idaho, hosts potential geothermal resources due to elevated groundwater temperatures associated with the thermal anomaly Yellowstone-Snake River hotspot. Project HOTSPOT has coordinated international institutions and organizations to understand subsurface stratigraphy and assess geothermal potential. Over 5.9km of core were drilled from three boreholes within the SRP in an attempt to acquire continuous core documenting the volcanic and sedimentary record of the hotspot: (1) Kimama, (2) Kimberly, and (3) Mountain Home. The Kimama drill site was set up to acquire a continuous record of basaltic volcanism along the central volcanic axis and to test the extent of geothermal resources beneath the Snake River aquifer. Data submitted by project collaborator Doug Schmitt, University of Alberta

Source: https://catalog.data.gov/dataset/kimama-wellborehole-geophysics-database

Last updated at https://catalog.data.gov/organization/doegov: 2017-08-29

License -Creative Commons Attribution

SHARED WITH- Everyone

CREATED- 5 years ago by @datagov-us

SIZE 552.57 MB

**TAGS- **downhole, geopysics, geothermal, idaho, kimama,neutron, pressure, resistivity, seismic, sonic, srp, tmepe rature

LICENSE CC-BY

Utah FORGE Seismic Stations and WellsGPS Survey Data, 2021

**Location- **Utah, USA

Description- This is a CSV spreadsheet containing UTM and Latitude and Longitude coordinates and elevations for Wells 78-32, 58-32, and 16A(78)-32 and BOR1, BOR2, BOR3, FOR2, FOR5, FORK, FORU, and FORW seismic stations. These are from a GPS survey conducted by the Utah Geological Survey in June, 2021.

**Link: **https://catalog.data.gov/dataset/utah-forge-seismicstations-and-wells-gps-survey-data-2021

Last updated at https://catalog.data.gov/organization/doegov: 2021-07-17

Fallon, Nevada Geophysics and Geochemistry Dataset

Location- Nevada, USA

Description- The data is associated to the Fallon FORGE project and includes mudlogs for all wells used to characterize the subsurface, as wells as gravity, magnetotelluric, earthquake seismicity, and temperature data from the Navy GPO and Ormat. Also included are geologic maps from the USGS and Nevada Bureau of Mines and Geology for the Fallon, NV area.

Tags- aeromag, egs, fallon, forge, geochemistry, geochemisty, geophysical, geophysics, geothermal, gravity, lidar, nevada, seismic, temperature

**Link- **https://catalog.data.gov/dataset/frontier-observatoryfor- research-in-geothermal-energy-fallon-nevada-9647d

Newberry EGS Datasets

Location- Multiple

Description- Datasets and information used to characterize the subsurface of Newberry and support modeling efforts. Includes sources for well logs, earthquakes, maps & crosssections, and LiDAR/DEM. Tags- dataset, dem, earthquakes, egs, forge, geothermal, lidar, model, newberry, newgen, oregon, seismic Link- https://catalog.data.gov/dataset/newberry-egsdatasets Geophysical and Geospatial Shapefiles from the Milford, Utah FORGE Project

Location- Multiple

Description- Three shapefiles in this submission show the position of proposed seismic line surveys. The mid-crustal velocity anomaly file shows the extent of an anomalously low Pwave velocity zone in the subsurface. Two other files show the extent of known hydrothermal systems in the Roosevelt Hot Springs area. Another file shows the location of the proposed water pipeline to pump water from the supply wells to the deep drill site.

Tags- arcgis, egs, forge, geothermal, gis, Geophysics, Well-log, hydrothermal, lines, milford, roosevelt, seismic, shapefile, system, utah

**Link- **https://catalog.data.gov/dataset/geophysical-andgeospatial- shapefiles-from-the-milford-utah-forge-project

Marine geoscience data management

**Location- ** Multiple

Description- The BGS manages marine data, information and material as part of the National Geoscience Data Centre (NGDC), the Marine Environment Data and Information Network (MEDIN) geology data archive centre (DAC) and the National Geological Repository (NGR). Geological, geophysical and environmental data on the seabed and sub-seabed is used to underpin the marine geoscience undertaken by the BGS and the wider user community in the UK and beyond. The data is used for a range of purposes, including the creation of BGS products. Data is freely available online (where possible) under OpenGeoscience and the Open Government Licence. However, some data are not yet processed for online delivery and in these cases there may be a charge to cover data preparation. You can also deposit data with us.

Tags- Marine, Geology, Geophysics

Link- https://www.bgs.ac.uk/geological-data/nationalgeoscience-data-centre/ngdc-data-management/marinegeoscience- data-management/

GEOLOGY: DATASETS

Location- Multiple

Description- Michigan GIS Open Data Portal- Here you can browse, search, preview, and download a variety of Michigan geospatial datasets. Browse by category or enter key words in the search box to locate a dataset of interest. You can then read its description to learn more and explore attributes before downloading. A variety of formats exist when downloading such as ESRI shapefile, spreadsheet, KML, or API.USGS Science Data Catalog- The USGS Science Data Catalog provides seamless access to USGS research and monitoring data from across the nation. Users have the ability to search, browse, or use a mapbased interface to discover data. Data.gov: Geology- This link will bring you to the U.S. Government's repository of data tagged 'geology'.National Geologic Map Database-A geoscience resource for maps and related data about geology, hazards, earth resources, geophysics, geochemistry, geochronology, paleontology, and marine geology.NOAA- The National Oceanic and Atmospheric Administration's National Centers for Environmental Information (NCEI) is responsible for preserving, monitoring, assessing, and providing public access to the Nation's treasure of geophysical data and information.AASG Geothermal Data Repository- Datasets collected as part of the AASG Geothermal Data System. Organized by geothermal data theme, and by state, this listing will probably be of most interest to geothermal domain scientists and engineers. PANGAEA- The information system PANGAEA is operated as an Open Access library aimed at archiving, publishing and distributing georeferenced data from earth system research. The system guarantees long-term availability of its content through a commitment of the hosting institutions. Most of the data are freely available and can be used under the terms of the license mentioned on the data set description. A few password protected data sets are under moratorium from ongoing projects. The description of each data set is always visible and includes the principle investigator (PI) who may be asked for access.Marine Geoscience Data System- The Marine Geoscience Data System (MGDS) provides a suite of tools and services for free public access to marine geoscience research data acquired throughout the global oceans and adjoining continental margins. The system evolved from projects initiated from 2003-2004 with funding from the National Science Foundation to provide data management services for the U.S. Antarctic Program (USAP), the Ridge 2000 and MARGINS programs, and for active source seismic data. In 2005, the system was expanded to include dedicated data management services for global bathymetry data. Since 2010, MGDS has been part of IEDA, an NSF-funded data facility for solid earth geoscience data.

Tags- GIS, Geothermal, Seismic, Geology, Exploration

Link- https://gis-michigan.opendata.arcgis.com

Indonesian Geological Resource

Location- Indonesia

Description- Geologically, Indonesia is a potential region for the formation of various energy and mineral resources. Exploration activities that have been carried out since 1800’s up to the present time, have successfully uncovered these resources in numerous areas. Among these various resources, oil, gas, coal, coal, tin, nickel, copper, and gold have so far given important contribution to the Indonesian economy. The majority of Indonesian territory has not been explored thoroughly, and therefore the chance to discover new economical energy and mineral deposit is likely to be substantial. https://www.oecd.org/env/2075532.pdf By : S. Suryantoro and M.H. Mana

Tags- Geology, Map, Mineral, Natural resources, Indonesia

Link- https://www.kaggle.com/code/mpwolke/indonesiangeological- resource

Wister, CA Downhole and Seismic Data

Location- Wister, USA

Description- This submission contains Downhole geophysical logs associated with Wister, CA Wells 12-27 and 85-20. The logs include Spontaneous Potential (SP), HILT Caliper (HCAL), Gamma Ray (GR), Array Induction (AIT), and Neutron Porosity (NPOR) data. Also included are a well log, Injection Test, Pressure Temperature Spinner log, shut in temperature survey, a final well schematic, and files about the well's location and drilling history. This submission also contains data from a three-dimensional (3D) multi-component (3C) seismic reflection survey on the Wister Geothermal prospect area in the northern portion of the Imperial Valley, California. The Wister seismic survey area was 13.2 square miles. (Resistivity image logs (Schlumberger FMI) in 85-20 indicate that maximum horizontal stress (Shmax) is oriented NNE but that open fractures are oriented suboptimally).

Tags- Seismic, Geophysics, Well-log, Geothermal

Link- https://catalog.data.gov/dataset/wister-ca-downholeand- seismic-data-daa1d

Dixie Valley Engineered Geothermal System Exploration Methodology Project, Baseline Conceptual Model Report

Location- Multiple

Description- The Engineered Geothermal System (EGS) Exploration Methodology Project is developing an exploration approach for EGS through the integration of geoscientific data. The Project chose the Dixie Valley Geothermal System in Nevada as a field laboratory site for methodlogy calibration purposes because, in the public domain, it is a highly characterized geothermal systems in the Basin and Range with a considerable amount of geoscience and most importantly, well data. This Baseline Conceptual Model report summarizes the results of the first three project tasks (1) collect and assess the existing public domain geoscience data, (2) design and populate a GIS database, and (3) develop a baseline (existing data) geothermal conceptual model, evaluate geostatistical relationships, and generate baseline, coupled EGS favorability/trust maps from +1km above sea level (asl) to -4km asl for the Calibration Area (Dixie Valley Geothermal Wellfield) to identify EGS drilling targets at a scale of 5km x 5km. It presents (1) an assessment of the readily available public domain data and some proprietary data provided by Terra-Gen Power, LLC, (2) a re-interpretation of these data as required, (3) an exploratory geostatistical data analysis, (4) the baseline geothermal conceptual model, and (5) the EGS favorability/ trust mapping. The conceptual model presented applies to both the hydrothermal system and EGS in the Dixie Valley region.

Tags- Hydrothermal, Geothermal, Geostatistics

Link- https://catalog.data.gov/dataset/dixie-valleyengineered- geothermal-system-exploration-methodologyproject- baseline-concept-fcc87

Newberry Well 55-29 Stimulation Data

Location- NewBerry, USA

Description- The Newberry Volcano EGS Demonstration in central Oregon, a 3 year project started in 2010, tests recent technological advances designed to reduce the cost of power generated by EGS in a hot, dry well (NWG 55-29) drilled in 2008. First, the stimulation pumps used were designed to run for weeks and deliver large volumes of water at moderate well-head pressure. Second, to stimulate multiple zones, AltaRock developed thermo-degradable zonal isolation materials (TZIMs) to seal off fractures in a geothermal well to stimulate secondary and tertiary fracture zones. The TZIMs degrade within weeks, resulting in an optimized injection/ production profile of the entire well. Third, the project followed a project-specific Induced Seismicity Mitigation Plan (ISMP) to evaluate, monitor for, and mitigate felt induced seismicity. Stimulation started October 17, 2012 and continued for 7 weeks, with over 41,000 m3 of water injected. Two TZIM treatments successfully shifted the depth of stimulation. Injectivity, DTS, and seismic analysis indicate that fracture permeability in well NWG 55-29 was enhanced by two orders of magnitude. This submission includes all of the files and reports associated with the geophysical exploration, stimulation, and monitoring included in the scope of the project.

Type- Well-log, Seismic, Bedrock

Link- https://catalog.data.gov/dataset/newberry-well-55-29-stimulation-data

Geophysical and Geospatial Shapefiles from the Milford, UtahFORGE Project

Location- Utah, USA

Description- Three shapefiles in this submission show the position of proposed seismic line surveys. The mid-crustal velocity anomaly file shows the extent of an anomalously low P-wave velocity zone in the subsurface. Two other files show the extent of known hydrothermal systems in the Roosevelt Hot Springs area. Another file shows the location of the proposed water pipeline to pump water from the supply wells to the deep drill site.

Tags- Geophysics, Geospatial, Subsurface

Link- https://catalog.data.gov/dataset/geophysical-andgeospatial-shapefiles-from-the-milford-utah-forge-project

Newberry Well 55-29 Stimulation Data 2014

Location- Newell, USA

Description- The Newberry Volcano EGS Demonstration in central Oregon, a 5 year project begun in 2010, tests recent technological advances designed to reduce the cost of power generated by EGS in a hot, dry well (NWG 55-29) drilled in 2008. First, the stimulation pumps used were designed to run for weeks and deliver large volumes of water at moderate well-head pressure. Second, to stimulate multiple zones, AltaRock developed thermo-degradable zonal isolation materials (TZIMs) to seal off fractures in a geothermal well to stimulate secondary and tertiary fracture zones. The TZIMs degrade within weeks, resulting in an optimized injection/ production profile of the entire well. Third, the project followed a project-specific Induced Seismicity Mitigation Plan (ISMP) to evaluate, monitor for, and mitigate felt induced seismicity. An initial stimulation was conducted in 2012 and continued for 7 weeks, with over 41,000 m3 of water injected. Further analysis indicated a shallow casing leak and an unstable formation in the open hole. The well was repaired with a shallow casing tieback and perforated liner in the open hole and re-stimulated in 2014. The second stimulation started September 23rd, 2014 and continued for 3 weeks with over 9,500 m3 of water injected. The well was treated with several batches of newly tested TZIM diverter materials and a newly designed Diverter Injection Vessel Assembly (DIVA), which was the main modification to the original injection system design used in 2012. A second round of stimulation that included two perforation shots and additional batches of TZIM was conducted on November 11th, 2014 for 9 days with an additional 4,000 m3 of water injected. The stimulations resulted in a 3-4 fold increase in injectivity, and PTS data indicates partial blocking and creation of flow zones near the bottom of the well. This submission includes all of the files and reports associated with the stimulation, pressure testing, and monitoring included in the scope of the project.

Tags- Well log, Bedrock, Seismic, Drillcore

Link- https://catalog.data.gov/dataset/newberry-well-55-29-stimulation-data-2014-5f263

Seismic Data from Roosevelt Hot Springs, Utah FORGE Study Area

Location- Utah, USA

Description- This set of data contains raw and processed 2D and 3D seismic data from the Utah FORGE study area near Roosevelt Hot Springs. The zipped archives numbered from 1-100 to 1001-1122 contain 3D seismic uncorrelated shot gatherers SEG-Y files. The zipped archives numbered from 1-100C to 1001-1122C contain 3D seismic correlated shot gatherers SEG-Y files. Other data have intuitive names.

Tags- Seismic, Well-log, Bedrock,

**Link- ** https://gdr.openei.org/submissions/1015

Silver Peak Innovative Exploration Project

Location- Esmeralda County, Nevada, USA

Description- Data generated from the Silver Peak Innovative Exploration Project, in Esmeralda County, Nevada, encompasses a deep-circulation (amagmatic) meteoric-geothermal system circulating beneath basin-fill sediments locally blanketed with travertine in western Clayton Valley (lithium-rich brines from which have been mined for several decades). Spring- and shallow-borehole thermal-water geochemistry and geothermometry suggest that a Silver Peak geothermal reservoir is very likely to attain a temperature range 260- 300oF (~125-150oC) , and may reach 300-340oF (~150-170oC) or higher (GeothermEx, Inc., 2006). Results of detailed geologic mapping, structural analysis, and conceptual modeling of the prospect (1) support the GeothermEx (op. cit.) assertion that the Silver Peak prospect has good potential for geothermal-power production; and (2) provide a theoretical geologic framework for further exploration and development of the resource. The Silver Peak prospect is situated in the transtensional (regional shearing coupled with extension) Walker Lane structural belt, and squarely within the late Miocene to Pliocene (11 Ma to ~5 Ma) Silver Peak-Lone Mountain metamorphic core complex (SPCC), a feature that accommodated initial displacement transfer between major right-lateral strike- slip fault zones on opposite sides of the Walker Lane. The SPCC consists essentially of a ductiley-deformed lower plate, or core, of Proterozoic metamorphic tectonites and tectonized Mesozoic granitoids separated by a regionally extensive, low-angle detachment fault from an upper plate of severely stretched and fractured structural slices of brittle, Proterozoic to Miocene-age lithologies. From a geothermal perspective, the detachment fault itself and some of the upper-plate structural sheets could function as important, if secondary, subhorizontal thermal-fluid aquifers in a Silver Peak hydrothermal system.

Tags- Hydrothermal, Geothermal, Minerals

Link- https://catalog.data.gov/dataset/silver-peak-innovativeexploration-project-ram-power-inc-fa599

Fallon FORGE: Geophysics and Geochemistry

Location- Silver Peak, USA

Description- The data is associated to the Fallon FORGE project and includes mudlogs for all wells used to characterize the subsurface, as wells as gravity, magnetotelluric, earthquake seismicity, and temperature data from the Navy GPO and Ormat. Also included are geologic maps from the USGS and Nevada Bureau of Mines and Geology for the Fallon, NV area.

Tags- Geology, Geophysics, Well-log, Geochemistry

Link- https://catalog.data.gov/dataset/fallon-forgegeophysics-and-geochemistry

Brady's Geothermal Field Nodal Seismometers Metadata

Location- Multiple

Description- Metadata for the nodal seismometer array deployed at the POROTOMO's Natural Laboratory in Brady Hot Spring, Nevada during the March 2016 testing. Metadata includes location and timing for each instrument as well as file lists of data to be uploaded in a separate submission. Tags- Seismic, Geothermal,Metadata Link- https://catalog.data.gov/dataset/bradys-geothermalfield- nodal-seismometers-metadata-0f580 Kansas Geological Survey Well- Log Dataset Location- Kansas, USA Description- This data set is collected from Kansas Geological Survey, data is available for public use and may be distributed or copied. The user is granted the right, without any fee or cost, to access, link to and use, publish, distribute, disseminate, transfer, or in any manner alter, modify, revise, copy, edit, or digitize this information. It is unlawful to falsely claim copyright or other rights in KGS material. The user must include an appropriate citation crediting the source of all or any portion of this website and its contents as follows: If the user does reuse or redistribute information contained on this site, the user acknowledges that KGS or its affiliates, retains a nonexclusive, royalty-free, perpetual, irrevocable, and full right to use, reproduce, modify, adapt, publish, translate, create derivative works from, distribute, and display the original information throughout the world in any media. KGS expressly disclaims the applicability of the Uniform Computer Information Transactions Act (UCITA). This is a well log file which contains approximately 8000 lines of data containing data of Resistivity, Spontaneous Potential, Gamma ray, Bulk density, Neutron and density porosity data. The data can be used to experiment and train small deep learning models, Which can further be transferred to big datasets.

Type- Well-log, Geology, Seismic,

Link- http://www.kgs.ku.edu

https://www.kaggle.com/datasets/prateekvyas/well-log-data

Newberry Well 55-29 Stimulation Data 2014

Location- Newell, USA

Description- The Newberry Volcano EGS Demonstration in central Oregon, a 5 year project begun in 2010, tests recent technological advances designed to reduce the cost of power generated by EGS in a hot, dry well (NWG 55-29) drilled in 2008. First, the stimulation pumps used were designed to run for weeks and deliver large volumes of water at moderate well-head pressure. Second, to stimulate multiple zones, AltaRock developed thermo-degradable zonal isolation materials (TZIMs) to seal off fractures in a geothermal well to stimulate secondary and tertiary fracture zones. The TZIMs degrade within weeks, resulting in an optimized injection/ production profile of the entire well. Third, the project followed a project-specific Induced Seismicity Mitigation Plan (ISMP) to evaluate, monitor for, and mitigate felt induced seismicity. An initial stimulation was conducted in 2012 and continued for 7 weeks, with over 41,000 m3 of water injected. Further analysis indicated a shallow casing leak and an unstable formation in the open hole. The well was repaired with a shallow casing tieback and perforated liner in the open hole and re-stimulated in 2014. The second stimulation started September 23rd, 2014 and continued for 3 weeks with over 9,500 m3 of water injected. The well was treated with several batches of newly tested TZIM diverter materials and a newly designed Diverter Injection Vessel Assembly (DIVA), which was the main modification to the original injection system design used in 2012. A second round of stimulation that included two perforation shots and additional batches of TZIM was conducted on November 11th, 2014 for 9 days with an additional 4,000 m3 of water injected. The stimulations resulted in a 3-4 fold increase in injectivity, and PTS data indicates partial blocking and creation of flow zones near the bottom of the well. This submission includes all of the files and reports associated with the stimulation, pressure testing, and monitoring included in the scope of the project.

**Tags-** Well-log, Seismic,Stimulation

**Link-** https://data.world/us-doe-gov/49b68478-9eb9-48b4-a105-5d7e43b7bfab

**Athabasca Oil Sands Data McMurray/Wabiskaw Oil SandsDeposit - Electronic Data**

**Location-**

**Description-** This is the digital database that is described in our Open File Report 1994-14. The database is implemented on a VAX station 4000 using INGRES, a commercially available database management system. It contains data on 2193 wells, including about 750 wells that have core analyses. In 1986, Alberta Geological Survey began a project to map the McMurray Formation and the overlying Wabiskaw Member of the Clearwater Formation in the Athabasca Oil Sands Area. The data that accompany this report are one of the most significant products of the project and will hopefully facilitate future development of the oil sands.Tagsascii file bitumen data digital data geology lithology log analysis natural gas oil sands porosity stratigraphic picks stratigraphy volume of shale wabiskaw water saturation well log data

**Link-** https://ags.aer.ca/publication/spe-006

**Explore Queensland`s mining and exploration data**

**Location-** Queensland, Australia

**Description-** Featured datasets Kamilaroi 61,368 line km regional airborne magnetic and radiometric survey flown at 100m line interval north of Mount Isa under the New Economy Minerals Initiative by the GSQ in 2021 Data type- Magnetic Created-19 Oct 2021 Data Format-gdb, ZIP, tif, PDF Central Isa Airborne magnetic and radiometric geophysical survey flown by Thomson Aviation for the Geological Survey of Queensland in 2019-2020 Data type- Magnetic Created- 23 Sep 2020 Data Format-PDF, gdb, grd, gi, tif, ZIP, JSON Mount Isa Region Airborne Data Merge 2022 The Mount Isa Region Airborne Data Merge 2022 product was created from a merge of recent high-resolution regional GSQ airborne magnetic and radiometric surveys and some open-file exploration surveys in the North West Mineral Province. The 2022 data merge covers a larger region than the

****[Mount Isa (...)**

**Data type-** Magnetic

**Created-** 14 Mar 2022

**Data Format-** ZIP, TIFF

The Strategic Resources Exploration Program (https://www.resources.qld.gov.au/mining-resources/ initiatives/strategic-resources-exploration-program)** (SREP) was proposed to expand resource exploration and development for base metals and gas in North West Queensland. SREP forms a key component of (...) Data type-Dataset Created-11 Jul 2021 Data Format-PDF SEISMIC HEAD UPDATE PROJECT (SHUP) 2D KINGDOM PROJECT 2016

A Kingdom software project created by GSQ in 2016 as part of the Seismic Header Update Project (SHUP) contained all the SEGY included in the project.Data type

**Dataset Created-** 07 Dec 2021

**Data Format** ZIP

Explore by data type Spectral0 27

**Seismic-** 1357 Report 94267

**Radiometric 765**

Map collection 10726

Magnetotelluric 16

Magnetic 1015

Gravity-gradiometry 19

Gravity 113

Geochemistry 7275

Electromagnetic 157

Electrical 4 Dataset 91 Borehole 60397

Tags- Magnetic, Geology, Mining, Geophysics,

Link- https://geoscience.data.qld.gov.au/data/dataset

**National Offshore Petroleum Information Management System (NOPIMS)**

**Location-** Multiple

Description- Geoscience Australia has developed the National Offshore Petroleum Information Management System (NOPIMS) as an online data discovery and delivery system for all Australian offshore petroleum wells and survey information. The National Offshore Petroleum Information Management System (NOPIMS) has been developed to provide access to wells and survey data acquired primarily in Commonwealth waters and submitted under legislation, currently the Offshore Petroleum and Greenhouse Gas Storage Act 2006. This data can be downloaded or packaged on request. NOPIMS has been upgraded so as to provide access to over 1 million records related to survey and well activities undertaken primarily offshore Australia. The data can be directly accessed and downloaded whenever a digital version exists and meet the current system size requirements. Any other item can be requested via the online order mechanism and will be packaged and shipped on demand as per user requirements. Direct access to petroleum mining sample information is available on NOPIMS platform via the Core Library tab. Request to access those samples can also be made via the form available on NOPIMS. https://nopims.dmp.wa.gov.au/Nopims/RequestForms/ CoreCuttingsAccess/CoreCuttingsAccess Paper documents, legacy data submitted on 7 and 9.5 track reels and large SEGY datasets will be progressively migrated to NOPIMS In the meantime, these items can be requested directly from Geoscience Australia by contacting AusGeoData@ga.gov.au

Key Features • No registration required • Access to metadata for over 1 million asset • Reprocessed datasets catalogued and listed under a different tab for ease of search • Access to the Core Information Management System (CIMS) via the Core Library tab

**Tags-** Geophysics, Petroleum, Geoscience

**Link-** https://nopims.dmp.wa.gov.au/Nopims/

**Poseidon NW Australia Location- New South Wales, Australia**

**Description-** The Poseidon 3D Marine Surface Seismic Survey (Poseidon 3D) was acquired during the period October 2009 to March 2010 within Browse Basin exploration permits WA-315-P and WA-398-P, operated by ConocoPhillips (Browse Basin) Pty Ltd (ConocoPhillips). The survey ingresses the adjacent WA-314-P, WA-30-R, WA- 274-P and WA-411-P tenements. The survey area is located approximately 350km offshore north of Broome in Western Australia (Figure 1). The primary objective of the Poseidon 3D was to provide subsurface coverage of the exploration permit WA-315-P and the northern portion of WA-398-P, where potential exploration prospects had been identified in Cretaceous and Jurassic formations, from interpretation of 2D and 3D seismic data recorded by earlier surveys. The Poseidon 3D completely covered the existing BKG06b 3D survey. The Poseidon 3D was conducted by CGGVeritas using the seismic vessel Geowave Voyager. Following mobilisation of the vessel recording commenced on 3rd October 2009 and was completed on 3rd March 2010. The Poseidon 3D covers an area of 2,828km2 (Figure 2) and consists of 172 prime sail lines and 21 orthogonal lines in the area adjacent to the Seringapatam reef (appendix 1). The survey was acquired with sail lines oriented 130° / 310°.

**Tags-** Seismic, 3D Modelling, Well log, Petrophysics

**Link-** https://drive.google.com/drive/folders/0B7brcfeGK8Cbk9ueHA0QUU4Zjg?resourcekey=0-njGYrj9ZlE751Oi1-89sOg

**South Australian Resources Information Gateway**

**Description-** South Australian Resources Information Gateway. SARIG is a digital platform that delivers state wide geoscientific and spatial data.

**Tags-** Seismic, Geophysics, Geology, Well-log

**Link-** https://map.sarig.sa.gov.au/

**Digital Rocks Portal**

**Location-** Multiple

**Description-** Digital Rocks is a data portal for fast storage and retrieval, sharing, organization and analysis of images of varied porous micro-structures. It has the purpose of enhancing research resources for modeling/prediction of porous material properties in the fields of Petroleum, Civil and Environmental Engineering as well as Geology. This platform allows managing, preserving, visualization and basic analysis of available images of porous materials and experiments performed on them, and any accompanying measurements (porosity, capillary pressure, permeability, electrical, NMR and elastic properties, etc.) required for both validation on modeling approaches and the upscaling and building of larger (hydro)geological models.

**Tags-** Rock, Image, Crystal Structure 

**Link-** https://www.digitalrocksportal.org/
