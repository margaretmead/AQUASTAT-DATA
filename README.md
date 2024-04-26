# Food and Agriculture Association of the United Nations's Global Information System on Water and Agriculture (AQUASTAT)
## About
### This repository houses the publicly available AQUASTAT dataset, a collection of various indicators of human development, environmental health, and water management since 1960. It primarily focuses on data from African, South Asian, Asian, Latin American, and Caribbean nations. 
*This repository was created for Dr. Gotzler's English 105 class during the Spring 2024 semester at the University of North Carolina at Chapel Hill.* 

## Contents
Within this repository is:
* A [**datasets folder**](https://github.com/margaretmead/AQUASTAT-DATA/tree/main/datasets) that contains the raw AQUASTAT data, as well as two subsets of data from 2020 concerning GDP per capita and access to safe drinking water. These subsets were compiled using Python3.
* A [**data visualizations folder**](https://github.com/margaretmead/AQUASTAT-DATA/tree/main/data%20visualizations) that contains visualizations made with the subsets compiled in the **datasets** folder
* A [**process notebook**](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/aquastat_process.ipynb) that contains the methods used to compile these subsets from the raw data.

## Where is this data from?
This  repository contains the [AQUASTAT](https://data.apps.fao.org/aquastat/?lang=en) dataset, a publicly available dataset gathered by the [Food and Agriculture Organization of the United Nations](https://www.fao.org/aquastat/en/). 

## Purpose
The purpose of this repository is to serve as a public resource that potential policy-makers, researchers, and land developers can utilize to create accurate and reproducible datasets regarding the agricultural and economic development of countries.

## Potential Uses of this Data Include:
* Identifying economic trends in various nations over time
* Identifying trends in agricultural output over time
* Identifying areas of increased and/or unsustainable water usage
* Analyzing how these areas intersect and bringing awareness to the public and policy-makers to create and promote sustainability while maximizing a country's economic capacity

## Resources for Getting Started
* Access the [AQUASTAT](https://data.apps.fao.org/aquastat/?lang=en) and download the data as a .csv file
* Create an account with [Google Colab](https://colab.google/notebooks/) to follow the methods of data compilation listed in [aquastat_process](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/aquastat_process.ipynb)
* Create an account with the free website [DataWrapper](https://www.datawrapper.de/) to create data visualizations

## Visualizations
This map shows the AQUASTAT subset, countries_by_wealth. The gradient illustrates the distribution of GDP per Capita among countries of the world, allowing us to see where wealth is currently concentrated. This visualization was created with [DataWrapper](https://www.datawrapper.de/). 
![0Xmrq-gdp-per-capita](https://github.com/margaretmead/AQUASTAT-DATA/assets/156699907/c3a48ef0-7fd5-4f59-88e7-4e4407718ee5)

This bar graph shows a potential use of the countries_by_access subset. It graphs the percentage of each country's rural population that has access to safe drinking water, illustrating areas in which many people lack access to safe water. This visualization was created with [DataWrapper](https://www.datawrapper.de/). 
![countries-by-rural-population-with-access-to-safe-drinking-water](https://github.com/margaretmead/AQUASTAT-DATA/assets/156699907/a23bac11-4287-40ae-a9fd-748ea9917711)

## What do I do Next?
After reading this README page, you can navigate to the [**aquastat_process**]([https://github.com/margaretmead/AQUASTAT-DATA/blob/main/Process%20Notebook.ipynb](https://github.com/margaretmead/AQUASTAT-DATA/blob/main/aquastat_process.ipynb)) file. This contains a link to a step-by-step guide to reproducing the methods used to create the subsets used in the previous data visualizations!

You can also use those methods to mount the AQUASTAT data to your Google Drive and import it into Google Colab so that you can start refining it for your own research!
