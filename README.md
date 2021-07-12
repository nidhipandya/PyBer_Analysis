# PyBer_Analysis

## Overview of the Analysis

PyBer is a ride share company that has collected data from different types of cities that it operates in.  PyBer has asked for an analysis of a single quarter of data which should show relationships between city types and fare amounts.

The data being analyzed includes:
city types:
- Rural
- Suburban
- Urban
Types of data: 
- fare amounts
- number of drivers
- number of rides
- data averages, etc.


## Results:
The initial data frames were separate. For the analysis, the city_data and ride_data were merged using a LEFT JOIN and the pyber_data_df was created.

The PyBer summary df has a few components: Total Rides, Total Drivers, Total Fares, Avg Fare per Ride, and Avg Fare per Drivers.
![Pyber Summary](https://github.com/nidhipandya/PyBer_Analysis/blob/main/analysis/Pyber_Summary_df.PNG)
- As shown in the chart above, although rural cities have the fewest number of drivers and fares, the average fare per ride and average fare per driver is the highest among all three city types.  
- It seems that the oversaturation of drivers and fares in the urban cities have an inverse affect to the cost per share and the fare per driver. The low distance between destinations is probably another cause of lower fares per driver.
- The suburban fare totals are after the urban totals due to the distance between destination being further than urban cities.  Even though there are less drivers than the urban areas, the distance plays a key part in the fare amount.
- The rural areas have a higher fare per ride probably due to the distance between destinations being greater than suburban and urban cities.  The lower number of drivers also keeps the market saturation low which results in higher fares per driver.

![chart](https://github.com/nidhipandya/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

The chart above shows fare values at weekly intervals between January 2019 and April 2019. 

## Summary
### Recommendations
1. PyBer should assign drivers based on how busy a city is so that there is less market saturation.  This will lead to higher fares per driver.
2. PyBer should raise the fare rate for urban cities.  Another option for this could be to raise fares during peak and rush hours.
3. Pyber should also start a marketing campaign in rural areas to attract more drivers and modify fare rates to attract more business as well.
