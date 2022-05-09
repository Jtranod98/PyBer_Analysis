# PyBer_Analysis

Python, Jupyter Notebook, Pandas Library, CSV Files, Matplotlib

## Project Overview

The purpose of this project is to utilize Python, Pandas, and Matplotlib to create a summary table of the ride-sharing data by city type. Analyze all the rideshare data from January to end of April of 2019. Then, create a multiple-line graph that shows the total weekly fares for each city type. Last, submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources

- Software: Python 3.7, Jupyter Notebook, conda version 4.8.3, Pandas Library, SciPy, NumPy, Matplotlib 3.1.3
- Data Source: city_data.csv and ride_data.csv

## Results

### Ride-sharing data from data table 

   ![PyBer_sum_table.png](analysis/PyBer_sum_table.png)
   
- The data from the data-table showed:
  
	1. The total rides: 125 in rural cities, 625 in suburban cities, and 1625 in urban cities. The total rides in the urban cities is about 13X more than the rural cities and 2.6X more than the suburban cities.  There is a significant more rides in the urban cities.
    
	2. Total drivers: 78 in rural cities, 490 in suburban cities, and 2405 in urban cities. The total drivers in the urban cities is about 31X more than the rural cities and about 5X more than the suburban cities.  In respect to the number to rides in urban cities, there is too many drivers.
    
	3. Total fares: $4,327.93 in rural cities, $19,356.33 in suburban cities, and $39,854.38 in urban cities. The total fares in the urban cities is about 10X more than the rural cities and about 2X more than the suburban cities.  By looking at the total fares, the overall revenue is from the urban cities.
    
	4. Average fare per ride: $34.62 in rural cities, $30.97 in suburban cities, and $24.53 in urban cities. The average fare per ride in the urban cities is about $10 less than the rural cities and about $4 less than the suburban cities.  This showed rural cities generate the most money per ride.
    
	5. Average fare per driver: $55.49 in rural cities, $39.50 in suburban cities $39.50, and $16.57 in urban cities. The averager fare per driver in urban cities is about $39 less than the rural cities and about $16 less than suburban cities.  This analysis showed that rural cities generate the most money per driver.
    

### The graph of the total weekly fare by city type from January to April 2019.

 ![PyBer_fare_summary.png](analysis/PyBer_fare_summary.png)
 
   6. The above graph displayed the relationship of total weekly fare and city type. It is consistent with the table data; that the rural cities weekly total fares are significantly lower than the urban cities.  Also, the graph showed that there is a parallel relationship between city type in total fare; when one goes up the other also goes up.  For example, there was a peak at the last week of February, the total fare of all three type of cities also went up. Then, there was a slide right after, all cities also went down.

## Summary

- Based on the results, I see there are 3 problems that is affecting the revenue:  

 	1. The number of rides in rural cities is too low. 
  	2. The number of drivers in urban cities is too high.
  	3. The average fare per driver in urban cities is too low.
    
- Therefore, my recommendations, to increase the revenue, are:
    
	1. Lower the fare per ride in rural cities to encourage more riders.
	2. Reduce the number of drivers in urban cities.
	3. Increase the fare per ride in urban cities.



