# Food and Agriculture Association of the United Nations's Global Information System on Water and Agriculture (AQUASTAT)
## About
This repository was created for Dr. Gotzler's English 105 class during the Spring 2024 semester at the University of North Carolina at Chapel Hill. 

It contains the publicly available AQUASTAT dataset from the Food and Agriculture Organization of the United Nations. The AQUASTAT data repository is a collection of data about various indicators of human development, environmental health, and water management by country since 1960. It primarily focuses on the agricultural and economic capacities of African, South Asian, Asian, Latin American, and Caribbean nations. 

## Contents
This repository includes a Google Colab Notebook written in Python that contains a possible use case for the AQUASTAT data. The dataset was refined to include countries by GDP per Capita and by the percentage of each country's rural population that has access to safe drinking water. This information is contained in the following datasets:
* countries_by_wealth
* countries_by_access

The Notebook also subdivides the data into a subset of data containing countries in which less than 50% of the rural population has access to safe drinking water and whose GDP per capita is less than America's, based on data collected in the year 2020. This data is included in the datasets:
* less_than_us_gdppercapita
* half_safe_water_access

## Purpose
The Food and Agriculture Association of the United Nations collects AQUASTAT data to further its goal of promoting agricultural and rural development through sustainable water and land use. This data regarding agricultural development is primarily focused on developing nations, which can be aided in adopting sustainable practices that promote long-term health and productivity. Data regarding these agricultural and economic fields is therefore integral in research regarding ways to increase sustainability, increase agricultural output and food production, and promote public health and well-being. This repository is a reliable, accurate, and large-scale source of information that potential policy-makers, environmental researchers, land developers, and more can use to inform their decisions regarding the health of their country. 

## Where is this data from?
This  repository contains data from [AQUASTAT](https://data.apps.fao.org/aquastat/?lang=en), the publicly available dataset gathered by the [Food and Agriculture Organization of the United Nations](https://www.fao.org/aquastat/en/). 
The data subset was compiled using Google Colab through Python. 
