# Food and Agriculture Association of the United Nations's Global Information System on Water and Agriculture (AQUASTAT)
## About
### This repository houses the publicly available AQUASTAT dataset, a collection of various indicators of human development, environmental health, and water management since 1960. It primarily focuses on data from African, South Asian, Asian, Latin American, and Caribbean nations. 
*This repository was created for Dr. Gotzler's English 105 class during the Spring 2024 semester at the University of North Carolina at Chapel Hill.* 

## Contents
Within this repository is:
* A [**datasets folder**](https://github.com/margaretmead/AQUASTAT-DATA/tree/main/datasets) that contains the raw AQUASTAT data, as well as two subsets of data from 2020 concerning GDP per capita and access to safe drinking water. These subsets were compiled using Python3.
* A [**data visualizations folder**](https://github.com/margaretmead/AQUASTAT-DATA/tree/main/data%20visualizations) that contains visualizations made with the subsets compiled in the **datasets** folder
* A [**process notebook**](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/Process%20Notebook.ipynb) that contains the methods used to compile these subsets from the raw data.

## Where is this data from?
This  repository contains data from [AQUASTAT](https://data.apps.fao.org/aquastat/?lang=en), the publicly available dataset gathered by the [Food and Agriculture Organization of the United Nations](https://www.fao.org/aquastat/en/). 
The data subset was compiled using Google Colab through Python. This process can be viewed in the [compiling-subsets](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/compiling-subsets) file.

## Purpose
The purpose of this repository is to serve as a public resource from which accurate and reproducible data regarding the agricultural development of countries can be used to inform potential policy-makers, environmental researchers, land developers, and more to inform their public health and policy decisions. 

## Potential Uses of this Data
* Identifying economic trends in various nations over time
* Identifying trends in agricultural output over time
* Identifying areas of increased and/or unsustainable water usage
* Analyzing how these areas intersect and bringing awareness to the public and policy-makers to create and promote sustainability while maximizing a country's economic capacity

## Resources for Getting Started
* Access the [AQUASTAT](https://data.apps.fao.org/aquastat/?lang=en) and download the data as a .csv file
* Create an account with [Google Colab](https://colab.google/notebooks/) to follow the methods of data compilation listed in [compiling-satasets](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/compiling-subsets)
* Create an account with the free website [DataWrapper](https://www.datawrapper.de/) to create data visualizations

## Visualizations
This map shows the AQUASTAT subset, countries_by_wealth. The gradient illustrates the distribution of GDP per Capita among countries of the world, allowing us to easily see where wealth is currently concentrated. This visualization was created with [DataWrapper](https://www.datawrapper.de/). 
![0Xmrq-gdp-per-capita](https://github.com/margaretmead/AQUASTAT-DATA/assets/156699907/c3a48ef0-7fd5-4f59-88e7-4e4407718ee5)

This bar graph shows a potential use of the countries_by_access subset. It graphs the percentage of each country's rural population that has access to safe drinking water, illustrating areas in which many people lack access to safe water. This visualization was created with [DataWrapper](https://www.datawrapper.de/). 
![countries-by-rural-population-with-access-to-safe-drinking-water](https://github.com/margaretmead/AQUASTAT-DATA/assets/156699907/a23bac11-4287-40ae-a9fd-748ea9917711)

## What do I do Next?
After you finish reading this README page, you can navigate to the [compiling-subsets](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/compiling-subsets) file. This contains a link to the original AQUASTAT dataset .csv file and a step-by-step guide to mount it to your Google Drive and import it into Google Colab so that you can start refining it for your research needs! You can also view the already existing data frames created from the AQUASTAT data in the [datasets](https://github.com/margaretmead/AQUASTAT-DATA/tree/main/datasets) file. 
