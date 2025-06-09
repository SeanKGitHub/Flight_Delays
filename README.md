# Analysis of domestic US flight delays. 

This folder contains analyses of US flight delays between 2019 and August 2023. The frequency of delays is the primary focus of the analysis, how it varies by time, geography and airline. The decision tree and random forest models only contain data from 2019 and 2022, since the 2020 and 2021 data are so heavily affected by the Covid-19 lockdowns. 

## Contents
- 1_load_flights_2019-2023 loads and cleans the dataset and derives variables foe the analyses
- 2_EDA is an exploratory data analysis investigating how delay frequency varies by time of day, day of week, month, airline and airport.
- 3_Choropleths shows a map with the delay rate per State (by departures)
- 4_Routes_Viz contains visualisations of the top 100 flight routes in the data and indicates what percentage of flights on that route are delayed (limited to the top 100 as including all routes was too messy to follow). 
- Delay_Tree_Forest contains a decision tree and random forest model for predicting flight delays. It is tested with a real life example of a friend of mine's flights, with the details inputted and the predicted probability of delay output.

## Data
Airline Flight Delay and Cancellation Data, January 2019 - August 2023
US Department of Transportation, Bureau of Transportation Statistics: https://www.transtats.bts.gov
Source: https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023 

A tableau dashboard of a similar EDA as well as route/airport visualisations is available here: https://public.tableau.com/app/profile/se.n.king/viz/Flights_Analysis_17482221894770/Story1?publish=yes 
