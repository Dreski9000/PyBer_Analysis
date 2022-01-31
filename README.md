# PyBer_Analysis
UCB Data Science Bootcamp - Module 5 - PyBer and Matplotlib

### Analysis Overview

The purpose of this analysis is to examine PyBer ride sharing data across different city types - Urban, Suburban, and Rural, and to determine how the fare price, number of rides, and number of drivers is 
distributed among these city types / groups.

### Results

The vast majority of revenue from fares came from Urban ridesharing, which accounted for over 68% of all rides and 63% of all fares. Rural ridesharing accounted for only 5% of the total rides and 7% of total fares.

![Ride % Pie Chart](https://raw.githubusercontent.com/Dreski9000/PyBer_Analysis/main/analysis/Fig6.png)
![Fare % Pie Chart](https://raw.githubusercontent.com/Dreski9000/PyBer_Analysis/main/analysis/Fig5.png)

The average fare price appears to be inversely correlated to the number of drivers and number of rides per city type. Rural rides have the highest average fare per driver at $55 and highest average fare per ride at $35.

**Summary Statistics Table**:
![Summary Table](https://raw.githubusercontent.com/Dreski9000/PyBer_Analysis/main/analysis/pyber_summary_df.png)

Urban cities accounted for the majority of rides, drivers, and revenue from fares, however, the average fares were higher in suburban and rural cities.

*The bubble sizes correspond to the number of drivers in the following chart*
![Bubble Chart](https://raw.githubusercontent.com/Dreski9000/PyBer_Analysis/main/analysis/Fig1.png)

### Summary

In order to make useful recommendations, it may be necessary to expand our data set and perform more analysis with the following additional data:

    1. Distance metrics per ride, as this may be a confounding variable that determines the total cost of the ride, and may have significant correlation with city types.
    2. Driver ID logging - it is fair to assume that Driver A may have to travel from city X to city Y, which may be different city types, this could be another confounding variable in our analysis since we are assuming the drivers to be distinct in their respective areas.
    3. Any type of demand forecasting metrics - without understanding rider demand in respective location, it is difficult to make actionable business recommendations.

Nevertheless, here are some potential recommendations with the data at hand:
   
   1. Encouraging more drivers (via promotions etc.) to drive in Rural areas would likely lead to a decrease in average price per ride, and potentially encourage more people to try ridesharing.
   2.  Increasing average per ride fare / revenue in Urban cities would lead to the largest overall impact in revenue since this sector accounts for the most rides and drivers and appears to naturally have more demand.
