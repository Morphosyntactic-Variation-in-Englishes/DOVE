# DOVE 

## A socio-demographic Dataset fOr Varieties of English

DOI: tba

### About 

This dataset comprises extensive socio-demographic information for 71 spontaneous spoken varieties of English around the world. In total, DOVE comprises information on 16 extra-linguistic triggers (aka socio-demographic information) which can be broadly assigned to the categories geography, language contact/isolation, socio-history and demography. 

DOVE was compiled as part of the project [Extra-linguistic triggers of Morphosyntactic Variation in Englishes](https://sites.google.com/site/katlehret/research/MoVE) (MoVE) and was designed for studying the relationship between extra-linguistic triggers and morphosyntactic variation in spontaneous spoken English varieties, with a focus on language complexity. DOVE builds on and complements the information contained in the [electronic World Atlas of Varieties of English ](https://ewave-atlas.org/) (eWAVE), the currently largest database of morphosyntactic features in English varieties (Kortmann et al. 2020). 

### Overview of extra-linguistic triggers

Table 1: Overview of extra-linguistic triggers by category. Numbers provided in parentheses for each operationalised parameter refer to the section number in the documentation of sources.

| Category/construct | Operationalised parameter | Brief description | Variable name | 
| ------------- | ------------- | ------------- | ------------- |
| Geography  | Geographic spread  | Country size in km²; if applicable territory, region or land area for islands | spread |
|   | Coordinates  | Longitude and latitude WGS84 of the sociolinguistic centre/administrative centre/capital| longitude, latitude | 
|  |Region  |World region and micro region | region, region_micro |
|  Contact | Proportion of non-native speakers  | Calculated as the percentage of non-native speakers in relation to population size | prop_non-natives | 
|  | Number of contact languages   |  Languages spoken by at least 10% of the population of the respective country/territory; all L1 languages spoken in a country/territoty | contact_languages; all_L1 |
|   | Number of source languages  |  The contributing source language (only for pidgins and creoles), if known|  source_languages | 
||Official bilingualism/multilingualism  | Are two or more languages listed as official language(s)? | bilingualism (yes/no)|
|Socio-historical background|Variety type |Variety type as listed in [eWAVE 3.0](https://ewave-atlas.org/)| language_type |
|Society/demography|Number of native speakers  | Number of native speakers per national territory/variety | natives |
||Number of non-native speakers |Number of non- native speakers per national territory/variety|non-natives|
||Population size/Speech community |Number of native and non-native speakers in a given territory/country|population|
||Status as official language |Is English an official language? |official (yes/no)|
||Percentage of literacy  |Percentage of adult literacy 15+ both sexes|literacy, literacy_rounded |
| | Education  |Mean years of schooling | education|
|| Percentage of urban population  | Percentage of urban population| urban_pop |
||GNI |Gross national income per capita (GNI) | GNI|
||Migration rate |Net migration rate | migration|

### Sources

All information contained in DOVE is based on or was derived from open-access sources including governmental census data, non-governmental surveys and language projects, as well as published scientific work. Detailed information and acknowledgement of all sources is provided in the documentation together with licensing information and URLs (where applicable). All errors remain my own.

### File and folder structure

* :file_folder: data

  * languages_DOVE1.0_DDMonthYY.csv -- a spreadsheet containing socio-demographic information for English varieties and additional descriptive information such as variety name or abbreviation.

* :file_folder: documentation

  * geography.pdf -- definitions, description and detailed documentation of sources for geographic triggers.
  * contact.pdf -- definitions, description and detailed documentation of sources for triggers of language contact.
  * demography.pdf -- definitions, description and detailed documentation of sources for demographic and socio-historical triggers.
  * additional.pdf -- documentation of coding and sources for additional descriptive information.
  * appendix.pdf -- detailed description of estimation for English varieties in Suriname and French Guinea.


### Release note

DOVE v1.0 is currently not openly accessible and still partially under construction. The full dataset will be made publicly available in December 2026.

### Copyright and citation

> [!IMPORTANT]
> Individual data is subject to copyright and the terms and conditions indicated on the respective websites. The licence used here for publication was chosen based on the most restrictive licence in DOVE. This means that individual data may have less copyright restrictions. Beyond citation of this resource, reference to the individual sources is recommended.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

#### Cite as

Ehret, Katharina. 2025. DOVE - A socio-demographic Dataset fOr Varieties of English (v1.0). Zenodo.
DOI: tba

### Acknowledgements

As part of project MoVE, DOVE was generously funded by the [Fritz Thyssen Foundation](https://www.fritz-thyssen-stiftung.de/en/), Cologne, Germany, through Support of projects (grant no. 20.23.0.009SL).

Many thanks also go to my colleagues, all experts in one or more of the varieties comprised in this dataset for providing missing information on socio-demographic variables, helfpul suggestions and references to other sources (in alphabetical order): 

Robert Bailey, Laurie Bauer, Tobias Bernaisch, Ariane Macalinga Borlongan, Alfred Buregeya, David Britain, Sandra Clarke, Dagmar Deuber, Michael Ellis, Sabine Erhart, Sandra Evans, Nick Faraclas, Markku Filppula, Hans Fonka, Stephanie Hackert, Raymond Hickey, Magnus Huber, Bernd Kortmann, Jakob Leimgruber, Robert Mailhammer, Christian Mair, Miriam Meyerhoff, Michael Meyler, Bettina Migge, Salikoko Mufwene, Peter Mühlhäusler, Daniel Nkemleke, Stefanie Pillai, Raymond Oenbring, Heidi Quinn, Anna Rosen, Jeffrey Reaser, Mark Sebba, Jeff Siegel, Kingsley Ugwuanyi


