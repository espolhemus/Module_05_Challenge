# Module_05_Challenge
Module 05 Challenge - Ride Sharing Data Analysis

## Overview of Project
Module 5 Challenge. This project involves using Jupyter Notebooks, pandas, and matplotlib to import, manipulate, analyze and present visualizations of various data related to the business of PyBer, a ride sharing company.

### Purpose
The purpose of this challenge is to take one CSV file containing data related to the cities in which the company operates and a second CSV file relating to the individual rides completed using the company's platform, clean the data as necessary, and then use pandas and matplotlib to calculate relevant statistics related to the types of markets in which the company operates (classified as "Urban", "Suburban", and "Rural"), to create a visualization illustrating the performance of the each of the market segments in relation to one another, and to make recommendations based on any disparities observed between the various types of cities

## Summary of Results
The results of our Analysis of the data is as follows:

- The key metrics associated with our analysis of the PyBer data are:
    
![Summary Data Frame](/Images/DataFrame_Image.png)

![Fares by City Type](/Images/PyBer_fare_summary.png)

- For the period of time analyzed, within the cities for which data was provided, PyBer completed a total of 2,375 rides, with 2,973 drivers active within the platform.  The sum total of fares for the given period was $63,538.64; $4,327.93 associated with fares in Rural markets (6.81% of total fare revenue), $19,356.33 associated with fares in Suburban markets (30.46% of total fare revenue), and $39,854.38 associated with fares in Urban markets (62.72% of total fare revenue).

- The Average Fare per Ride in Rural markets was $34.62, the Average Fare per Ride in Suburban markets was $30.97, and the Average Fare per Ride in Urban markets was $24.53.    

- The Average Fare per Driver in Rural markets was $55.49, the Average Fare per Driver in Suburban markets was $39.50, and the Average Fare per Drver in Urban markets was $16.57.

## Business Recommendations
Based on our analysis, we would suggest that the company consider the following recommendations:

### Urban Driver Count

  - As illustrated by in the data frame image presented in the Summary of Results, for the period of time analyzed, it is likely that there were at least 780 drivers in Urban cities who did not complete at least one trip with Pyber; not only is this potentially an opportunity to drive incremental revenue growth, but this has a significant impact on the "Average Fare per Driver" values, and efforts should be undertaken to understand why the number of drivers exceeds the number of trips completed by such a wide margin.

### Lack of Granularity in Data

  - In order to provide the most useful insights, it would be extremely helpful if the ride-level data that we are provided with included a field identifying the driver associated with a particular ride; this will enable us to provide much more useful summary statistics, and to potentially identify ways in which the current summary data may not be truly representative of the experience of drivers partnering with the company.

### Focus on Driving Growth in Suburban Markets

  - Rides in Suburban markets accounted for 30.46% of Total Fares during the period, while only accounting for only 26.32% of Total Rides during the period, whereas rides within Urban markets accounted for only 62.72% of Total Fares during the period, while comprising 68.42% of Total Rides during the period.  Therefore, we would suggest that focusing on increasing ride growth within Suburban markets will deliver the greatest return on overall Fare Revenue. 
