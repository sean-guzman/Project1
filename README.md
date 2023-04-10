# Project 1

Cory Scarnecchia, Lauren Golden, Sean Guzman, Sincere

Rutgers Data Sciences Bootcamp, Project 1 (10 April 2023)

In this group project, we took data for Heart Disease and Stroke Mortality in the US from 1999 to 2019 to discover the progress the US has made as a country, how regions and individal states did. To break it down even further, we chose to go down to the local county level and selected New Jersey for it diversity and see whether location, population, and poverate rate can play some role, so we pull in data from the US Census API to help us generate this missing data from our dataset.

We first cleaned our dataset and then get down to breaking the data.  What we come find from a country level, regional/state level, and county (NJ) level is that the data for Heart Disease and Stroke Mortality trends downward from 1999 to 2019 which we can assume at this point is due to the increase in health education in areas such as tobacco, diabetes, and obesity.  Therefore, we bring in another dataset and clean it, and attempt to find a correlation between our original dataset and these other related conditions.


Files
1. main.ipynb - this script contains the majority of our work where data from our two data sources are cleaned and then broken down into smaller dataframes from a country down to the county level.  

2. Census API Pull.ipynb - this script is to pull census data from census.gov. Please note an API key stored in variable 'census_apikey' in file 'api_keys.py' will be required for this file to properly work.

3.Census API Poverty.ipynb - this script is to specifically pull poverty data from census.gov. Please note an API key stored in variable 'census_apikey' in file 'api_keys.py' will be required for this file to properly work.



Sources:

1. Rates and Trends in Heart Disease and Stroke Mortality Among US Adults (35+) by County, Age Group, Race/Ethnicity, and Sex – 2000-2019
https://catalog.data.gov/dataset/rates-and-trends-in-heart-disease-and-stroke-mortality-among-us-adults-35-by-county-a-2000-45659

2. U.S. Chronic Disease Indicators (CDI)
https://chronicdata.cdc.gov/Chronic-Disease-Indicators/U-S-Chronic-Disease-Indicators-CDI-/g4ie-h725
