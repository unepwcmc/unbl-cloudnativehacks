# SPATIAL DATA FOR BIODIVERSITY CONSERVATION

<img src="https://github.com/unepwcmc/unbl-cloudnativehacks/assets/141819111/b5e2ba08-7521-4d4e-892b-c43e1ab001bc" height="150"/>
     <img src="https://github.com/unepwcmc/unbl-cloudnativehacks/assets/141819111/d75e61e2-b26f-4c9a-981c-cc1f865081c8" height="150"/>
     <img src="https://github.com/unepwcmc/unbl-cloudnativehacks/assets/141819111/caa96421-9c25-4af0-87e2-2df107d5c127" height="150"/>

**Brief:** Leverage spatial data to uncover functional insights to monitor, protect and restore nature for people and the planet 

**Description:**  Forest loss, land and marine degradation, and species extinctions are escalating. These events pose severe threats to the survival of people and the planet. The Global Biodiversity Framework of the UN Biodiversity Convention provides renewed impetus for conserving terrestrial and marine ecosystems, in line with SDGs 13, 14, and 15.  

The [UN Biodiversity Lab](https://unbiodiversitylab.org/en/) (UNBL) is a web-based tool that supports governments, NGOs, and civil society to access relevant geospatial datasets to provide valuable insights about their territories, facilitating strategic decision making and smart reporting. Currently, UNBL is being further developed to align with the needs of countries in relation to the Global Biodiversity Framework to support spatial planning, monitoring, and reporting needs. Decision-makers need customized dashboards, analytics, and indicators that on the state of nature and trends over time to make key decisions for biodiversity conservation and sustainable development. 

We invite you to develop an attractive dashboard and/or widgets based on cloud-native datasets to offer more advanced analyses that enable governments to take action for nature, climate, and human well-being. 

In this document, we will publish some relevant datasets and give you some ideas to explore. We are still working on it. Stay tuned.

### Links
- [SDG 13: Climate Action](https://www.un.org/sustainabledevelopment/climate-change/)
- [SDG 14: Life Below Water](https://www.un.org/sustainabledevelopment/oceans/)
- [SDG 15: Life On Land](https://www.un.org/sustainabledevelopment/biodiversity/)

### Contact
Need some help / support, you can contact us:  
- [email](mailto:unbl@unep-wcmc.org)
- [Slack](cloud-native-hacks-aaaamjzzuyzpkclta7x7wfh5iu@wcmc.slack.com)

### Datasets

Here are some suggested datasets you could work on, but you can also select your own datasets.
- To access our datasets, ask for a token by [email](mailto:unbl@unep-wcmc.org) / [Slack](cloud-native-hacks-aaaamjzzuyzpkclta7x7wfh5iu@wcmc.slack.com)
- These datasets are global spatial data
- These datatasets are suggested because they are currently relevant, as they can be used to report on the [Global Biodiversity Framework](https://www.post-2020indicators.org/). 
- Countries adopted the [Global Biodiversity Framework](https://www.post-2020indicators.org/) at the 15th meeting of the Conference of the Parties (COP15) to the [Convention on Biological Diversity (CBD)](https://www.cbd.int/convention), held in December 2022.
- The Global Biodiversity Framework aims to put nature on a path to recovery. 
- The framework features [4 goals](https://www.cbd.int/gbf/goals/) and [23 targets](https://www.cbd.int/gbf/targets/) that span three broad topics: reducing threats to biodiversity, meeting people’s needs, and tools and solutions for implementation.
- The datasets are published as Cloud Native datasets: COG Geotiff for rasters and Geoparquet for vectors
- ⚠️ Don't forget to mention credits and be compliant with the respective license of each datasets. ⚠️

<br/><br/>

| #  | Dataset | Cloud Native Data | Other Format | 
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 1  | Protected Areas | [UNBL Azure Blob](https://cloudnativehacks.blob.core.windows.net/data/protected-areas/WDPA_Mar2024_Public.parquet)| |
| 2  | Global Pesticide Risk Scores |[UNBL Azure Blob](https://cloudnativehacks.blob.core.windows.net/data/global-pesticide-pollution-risk/Global_pesticide_risk_scores_cog.tif)| |
| 3  | Ecological Intactness Index | [UNBL Azure Blob](https://cloudnativehacks.blob.core.windows.net/data/ecological-intactness-index/Ecological-Intactness-Index_year-2009_Qprime_cog.tif)| |
| 4  | Biodiversity Habitat Index | [UNBL Azure Blob](https://cloudnativehacks.blob.core.windows.net/data/04_biodiversity-habitat-index/BILBI_P_BHIv2_Habitat_2020_cog.tif)  |
| 5  | Global Surface Water | [GEE](https://developers.google.com/earth-engine/datasets/catalog/JRC_GSW1_4_GlobalSurfaceWater)<br/>TBD - [UNBL Azure Blob]()  |
| 6  | Protected Area Connectivity | TBD - [UNBL Azure Blob]()  |
| 7  | Areas of Global Significance for Restoration | TBD - [UNBL Azure Blob]()  |
| 8  | Forest Structural Integrity Index | TBD - [UNBL Azure Blob]()  |
| 9  | Global Open Buildings | [Source.coop](https://beta.source.coop/repositories/vida/google-microsoft-open-buildings/description/) combined<br/>[GEE/VIDA](https://gee-community-catalog.org/projects/global_buildings/) combined <br/>[Google Earth Engine](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_Research_open-buildings_v3_polygons) <br/>[MS Planetary Computer](https://planetarycomputer.microsoft.com/dataset/ms-buildings)|  [OSM via Overpass](https://overpass-turbo.eu/s/1In5)|
|  10  | Biodiversity Intactness | [UNBL Azure Blob](https://cloudnativehacks.blob.core.windows.net/data/biodiversity_intactness_index/BIIAb-2015_cog.tif) <br/>[MS Planetary Computer](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) <br/>[GEE/EarthBlox](https://gee-community-catalog.org/projects/bii/)| |
|  11  | Country Boundaries | [UNBL Azure Blob]() <br/>[MS Planetary Computer]() <br/>[GEE/EarthBlox](https://gee-community-catalog.org/projects/bii/)| |




