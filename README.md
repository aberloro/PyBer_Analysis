# PyBer_Analysis

## Overview

### Background
Previous work has been done on this ride-share dataset to create [visualizations](https://github.com/aberloro/PyBer_Analysis/blob/a034f1fe1a4b6cb6897dfb01be5ec301b0ccbc96/PyBer.ipynb) that address the questions of access and affordability in underserved markets. A bubble plot showed an inverse correlation between average fare and total number of rides per city.  Box and whisker plots were provided for ride count, ride fare, and driver count data. These plots showed urban cities with the highest average ride and driver counts, and lowest average fares.  Rural city types had the highest average fares and the fewest available drivers and lowest number of trips. Pie chart visualizations showed fares by city type with urban cities claiming nearly two thirds of all fares, rides by city type with rural rides clocking in at only 5% of the total, and drivers per city type with rural cities only carrying about 3% of available drivers.  

### Purpose 
The PYBER CEO is looking at data with the goals of improving access and affordability to under-served areas.  The purpose of this project is twofold:
 1. Summarize the above ride-share data to show total rides, total drivers, total fares, average fare per ride, and average fare per driver for each of the three city types: urban, suburban, and rural. 
 2. Create a multi-line plot showing the total weekly fares for each city type from January through April, 2019. 


## Results

### Findings from the Ride-Share Summary DataFrame
Urban cities had the highest number of total rides, drivers, and fares while rural cities had the lowest and suburbs were inbetween.  The average fares per ride and average fares per driver were higher in rural cities and suburbs than in urban cities.  There is a correlative relationship between the city-type size and the number of rides, drivers, and total fares. There is an inverse relationship between city-type size and the cost per ride, likely because of the fewer available-drivers. See the ride-Share Summary DataFrame below: 

![RideShare_Summary_DataFrame](https://user-images.githubusercontent.com/93740725/151629158-17cf21da-560a-4648-9103-dbf07aa1b4f6.png)

### Findings from Weekly Rides Multi-Plot 
A plot of the weekly total fares shows a significant gap between urban and suburban / rural fares.  The urban fares tallied between January an April ranged from about $1600 to $2500, where suburban totals hovered between $700 and $1400 and rural totals stayed between $100 to $500.  Both suburban and urban plots showed slight growth between January and April, where the rural line stayed relatively flat.  In general the three plots did not trace the same peaks and vallies over time, with the exception of the third week of February where all three plots hit a peak.  See the Fare Summary Plot below:

![Pyber_fare_summary](https://user-images.githubusercontent.com/93740725/151625938-bac75b10-5e7b-4ed9-a721-da0a6f860b4b.png)

## Summary
The biggest disparity in access to ride-shares is apparent in rural city types, where only 2.6% of all drivers operate.  This would make it challenging for rural riders to find quick and convenient service.  One recomendation is to increase the number of drivers to rural cities to improve access.  This would also improve ridership because it should deccrease wait-times assiciated with lack of drivers. 

A second disparity seen in rural cities is the average cost per ride: it is about $10 higher in rural cities over urban cities.  Of course, you expect to see more sprawl (longer rides) in rural areas, so a second recomendaiton to improve access would be to subsidize the cost of trips in rural areas to more closely match  trip cost in the suburbs or urban areas. This would incentivize ridership and thus increase demand for drivers.

A third disparity can be seen in available-drivers in the suburbs.  There are nearly 5x more drivers in urban city types than in suburban areas.  Incentiving drivers to operate in the suburbs should help bolster ridership and access there, as well as improve affordability.




