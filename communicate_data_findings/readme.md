# A Visual Exploration of Conflict Data from Brazil
## by Jessica Ertel

## Problem Statement
The goal of this project is to develop visualizations and accompanying analyses to better understand the nature of conflict in Brazil from the beginning of 2019 to present (May 2020).

## Dataset
This dataset was aquired via the [Humanitarian Data Exchange (HDX)](https://data.humdata.org/) and shared by the [Armed Conflict Location & Event Data Project (ACLED)](http://www.acleddata.com/). The dataset contains information on the type, agents, exact location, date, and other characteristics of political violence events, demonstrations and select politically relevant non-violent events. It is updated weekly on HDX and can be downloaded [here](https://data.humdata.org/dataset/acled-data-for-brazil). 

## Assessment and Cleaning
While the dataset was structurally sound and of good quality, some steps were taken to improve clarity for the purposes of this analysis. This included changing column names and data types.
- `admin1` and `admin2` columns were updated to `state` and `municipality` per the information in ACLED's Methodology and Coding Decisions
- data types were updated for the `fatalities`, `event date`, `latitude` and `longitude` columns
- 8 columns were dropped that contained repeated information

## Summary of Findings
This dataset evidences 14,222 conflict events in Brazil throughout 2019 and in the first trimester of 2020. 46.5% of these events were deadly - involving fatalities of one or more people. Rio de Janeiro state had by far the highest number of events and the highest number of fatalities in Brazil. While the Southeastern states of Rio de Janeiro, Minas Gerais and Sao Paulo had a high number of events, the states in Northeastern Brazil saw a higher number of fatalities. Minas Gerais and São Paulo's conflicts are largely peaceful protests, wheras Rio de Janeiro is predominantly armed clashes. The geopolitical landscape plays a role here, but it was hard to get a sense of seasonality or trends in the timing of conflict events without a longer timeframe.

