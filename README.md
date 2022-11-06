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

Urban cities had the most rides, most drivers, and highest accumulated fares. However, rural drivers, on average, earned more per each ride. These results are not suprising. There are more people living in urban cities than in rural areas, thus, more people use the ride-share services and more drivers are required. Furthermore, rides in cities are often a shorter distance, so the fare earned is lower. 

It's hard to make recommendations about future business activities without analyzing more data. For instance, I would like to calculate average fare per minute duration of trip. PyBer uses distance as a metric to estimate fares. The urban rides are often a shorter distance, thus, the fares earned per ride are lower. However, because of heavy traffic in some urban centers, the time per ride may be the same between a lot of urban and rural or suburban rides. 

* Because the fare per driver is so much higher in rural areas, it may incentivize drivers to spend more of their time in rural areas instead of the city where they are most needed. To account for this discrepany, fares could be adjusted for time or urban drivers could be compensated with a higher base rate of pay. 

* If demand in urban areas is much higher than the drivers available, consider isntituting surge pricing to maximize earnings.

* Consider analyzing ride-share users per driver for each city type. Make sure the supply of drivers adequately meets the demand, especially in rural areas where fares are so high. 
