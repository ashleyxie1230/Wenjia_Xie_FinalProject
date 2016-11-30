# Wenjia_Xie_FinalProject
## Goal of the Project
In this project I want see the murder rate and poverty rate by state in the U.S., and explore if there's ant statistical association between poverty rate and murder rate. 
The datasets are listed below:
Number of Poor and Poverty by State (1980-2015)
http://www.census.gov/data/tables/time-series/demo/income-poverty/historical-poverty-people.html
Nationwide Murder Rates by State
http://www.deathpenaltyinfo.org/murder-rates-nationally-and-state
## Merging the Data  
The goal of merging is to use State and Year as keys. The raw data isn't suitable for merging, so i use the code to transfer it into something that can be merged. Same for the Murder rate data. The merged data includes data from 2006-2014 and state and year are keys. 
## Scatterplot
Do linear regression with the merged data and present a twoway linear prediction plots. We see that there's positive statistical association between murder rate and poverty rate
## Mapping
The shade of color of states represent the degree of poverty and murder rate respectively in the two maps. First. calculate the mean of every state's poverty rate and murder rate and use the means to benchmark on the map. 
Use GeoPandas to generate two maps. We can see there's some similar trends between two maps (i.e., the colors that are deeper in poverty rates tend to be also deep in terms of murder rates.
