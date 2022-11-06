# PyBer_Analysis

## Overview
For this challenge, I was tasked with using Python to analyze rideshare data from a ficticious ride-share company called PyBer. The data was broken down by city type (Urban, Suburban, Rural). 

### Resources
 * Data Source: city_data.csv, ride_data.csv
 * Software: Python 3.7.1, Jupyter Notebook 

## Deliverable 1: Summarize Ride-Share Data by City Type
Each city that utilizes the PyBer ride-share system was categorized as either Urban, Suburban, or Rural. My first task was to determine each how city type differed in metrics such as total number of rides, total number of drivers, and total fares. 

Furthermore, I calculated the average fare per ride and the average fare earned per driver for each city type. The results of these analyses can be seen in the summary table below:

### Results
![Rideshare DataFrame](https://github.com/CSoldo1/PyBer_Analysis/blob/main/PyBer_Summary_Dataframe.PNG)

## Deliverable 2: Total Fares for each City Type
By grouping and resampling the data, I was able to assess the total fares collected by city type from January 1, 2019 to April 28, 2019. 

First, the date was set as the index for the data frame. 

![Date as the index](https://github.com/CSoldo1/PyBer_Analysis/blob/main/Del_2.1.PNG)

The total amount of fares collected at each date and time for each city type was summarized in a data frame. 

![Data Frame 2](https://github.com/CSoldo1/PyBer_Analysis/blob/main/Del_2.2.PNG)

### Results

![Total Fares by City Type](https://github.com/CSoldo1/PyBer_Analysis/blob/main/PyBer_fare_summary.png)

## Summary
