``# SPATIAL DATA FOR BIODIVERSITY CONSERVATION

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
- [Slack](mailto:cloud-native-hacks-aaaamjzzuyzpkclta7x7wfh5iu@wcmc.slack.com)

### Datasets

Here are some suggested datasets you could work on, but you can also select your own datasets.
1) To access our datasets, **ask for a token** by [email](mailto:unbl@unep-wcmc.org) / [Slack](cloud-native-hacks-aaaamjzzuyzpkclta7x7wfh5iu@wcmc.slack.com)
2) These datasets are global spatial data
3) These datatasets are suggested because they are currently relevant, as they can be used to report on the [Global Biodiversity Framework](https://www.post-2020indicators.org/). 
4) Countries adopted the [Global Biodiversity Framework](https://www.post-2020indicators.org/) at the 15th meeting of the Conference of the Parties (COP15) to the [Convention on Biological Diversity (CBD)](https://www.cbd.int/convention), held in December 2022.
5) The Global Biodiversity Framework aims to put nature on a path to recovery. 
6) The framework features [4 goals](https://www.cbd.int/gbf/goals/) and [23 targets](https://www.cbd.int/gbf/targets/) that span three broad topics: reducing threats to biodiversity, meeting people’s needs, and tools and solutions for implementation.
7) The datasets are published as Cloud Native datasets: COG Geotiff for rasters and (Geo)parquet for vectors.
8) ⚠️ Don't forget to mention credits and be compliant with the respective license of each datasets. ⚠️

<br/>

| #  | Dataset | Type | How this data could be useful | Cloud Native Data Access | 
| ------------- | ------------- | ------------- | ------------- | ------------- | 
|  0  | Country Boundaries | vector | <sub>to get the polygon of countries so that you can report at national level or aggregate stats by country. </sub> | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/00_country-boundaries/ne_10m_admin_0_countries_wgs84.parquet?_asked_for_sas_token_by_email)<br/>+ [GEE <sup>2</sup>/GAUL](https://developers.google.com/earth-engine/datasets/catalog/FAO_GAUL_2015_level0)|
| 1  | Protected Areas<br/><sub>(only WDPA Polygons)</sub> | vector | <sub>to report the percentage coverage of terrestrial and marine areas covered by protected areas. (Target 3: Conserve 30% of Land, Waters and Seas.) ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates=0,0,0&layers=wdpa-protected-areas_100))</sub> | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/protected-areas/WDPA_Mar2024_Public.parquet?_asked_for_sas_token_by_email)</sub>|
| 2  | Global Pesticide Risk Scores | raster |<sub> to report exposure of agricultural land to pesticide pollution. Value range is from 0 (lowest exposure) to 6.1 (highest exposure). (Target 7: Reduce Pollution to Levels That Are Not Harmful to Biodiversity.) ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates=0,0,0&layers=risk-of-pesticide-pollution-at-the-global-scale_100))</sub>| <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/global-pesticide-pollution-risk/Global_pesticide_risk_scores_cog.tif?_asked_for_sas_token_by_email)</sub>|
| 3  | Ecological Intactness Index | raster | <sub>to capture both habitat loss, quality and fragmentation effects which, when combined, are called intactness. To identify areas that are a priority for retention of intact / wilderness areas. (Target 1: Plan and Manage all Areas To Reduce Biodiversity Loss.) ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates=0,0,0&layers=ecological-intactness-index_100))</sub> | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/ecological-intactness-index/Ecological-Intactness-Index_year-2009_Qprime_cog.tif?_asked_for_sas_token_by_email)</sub>|
| 4  | Biodiversity Habitat Index | raster | <sub>to monitor and report past-to-present trends in the expected persistence of species diversity by repeatedly recalculating the indicator using best-available mapping of ecosystem condition or integrity observed at multiple points in time, e.g., for different years (Goal A) ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates=0,0,0&layers=biodiversity-habitat-index-2000-2020-v2-30s-global-time-series_100))</sub> | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/04_biodiversity-habitat-index/BILBI_P_BHIv2_Habitat_2020_cog.tif?_asked_for_sas_token_by_email) </sub> |
| 5  | Global Surface Water | raster | <sub>to inform changes in water state, e.g. new permanent water surfaces, unchanging permanent water surfaces, lost permanent water surfaces, new seasonal water surfaces, etc. ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates=0,0,2&layers=global-surface-water-transitions-2000-2018-sdg-661-indicator_100))</sub> | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/05_global-surface-water/GSWE-aggregated-latest_transitions_cog.tif?_asked_for_sas_token_by_email) <br/>+ [GEE <sup>2</sup>](https://developers.google.com/earth-engine/datasets/catalog/JRC_GSW1_4_GlobalSurfaceWater) <br/>+ [MS PC <sup>1</sup>](https://planetarycomputer.microsoft.com/dataset/jrc-gsw)|
| 6  | Protected Area Connectivity | vector | <sub>to inform the percentage of each terrestrial ecoregion that is covered by protected connected lands. (Target 3: Conserve 30% of Land, Waters and Seas.) ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates0,0,0&layers=protected-area-connectivity_100))</sub> | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/06_protected-connected-index/protected_connected_index_by-ecoregion_2021_wgs84.parquet?_asked_for_sas_token_by_email) </sub> |
| 7  | Areas of Global Significance for Restoration | raster | <sub>to inform the preliminary results of a global prioritization analysis for the restoration of habitats for terrestrial species and carbon sequestering. (Target 1: Plan and Manage all Areas To Reduce Biodiversity Loss.) ([see on UNBL](https://map.unbiodiversitylab.org/earth?basemap=grayscale&coordinates=0,0,0&layers=areas-of-global-significance-for-restoration_100)) | <sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/07_global-significance-for-restoration/global-significance-for-restoration_Restoration_priority_v2_0_nearest-res001dd-wgs84_cog.tif?_asked_for_sas_token_by_email) </sub> |

<sub><br/><sup>1</sup> MS PC = Microsoft Planetary Computer Hub
<br/><sup>2</sup> GEE = Google Earth Engine</sub>

### Additional Datasets

| #  | Dataset | How this data could be useful | Cloud Native Data Access | 
| ------------- | ------------- | ------------- | ------------- | 
| 8  | Forest Structural Integrity Index | raster | <sub>To be done</sub> | <sub>+ TBD - [UNBL Blob]() </sub> |
| 9  | Global Open Buildings | vector | <sub>To be done</sub> | <sub>+ [Source.coop](https://beta.source.coop/repositories/vida/google-microsoft-open-buildings/description/) combined<br/>+ [GEE<sup>2</sup>/VIDA](https://gee-community-catalog.org/projects/global_buildings/) combined <br/>+ [Google Earth Engine](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_Research_open-buildings_v3_polygons) <br/>+ [MS PC<sup>1</sup>](https://planetarycomputer.microsoft.com/dataset/ms-buildings)<br/>+ [OSM via Overpass](https://overpass-turbo.eu/s/1In5)</sub>|
|  10  | Biodiversity Intactness Index | raster | <sub>To be done</sub> |<sub>+ [UNBL Blob](https://cloudnativehacks.blob.core.windows.net/data/10_biodiversity-intactness-index/BIIAb-2015_cog.tif?_asked_for_sas_token_by_email) <br/>+ [MS PC](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) <br/>+ [GEE<sup>2</sup>/EarthBlox](https://gee-community-catalog.org/projects/bii/)</sub>|
