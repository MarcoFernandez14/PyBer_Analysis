# PyBer_Analysis
## Purpose of the Analysis
The purpose of the analysis is to perform an exploratory analysis on data in large csv files. The aim is to create several types of visualizations to tell a compelling story showcasing the relationship between the type of city and the number of drivers and rides. The analysis is meant to help Pyber improve access to ride-sharing services and determine affordability for under-served neighborhoods.
The final assignment is to create (using Python, Pandas and Matplotlib) a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type.

### Evironment
Python 3.7.3  
Anaconda 1.9.0  
Conda 4.12.0  
Jupyter notebook 6.1.12  
Pandas 1.3.4  
Matplotlib 3.4.3  

## Results
### Data
In order to understand the differencies of the service by type of city, the ride-sharing data was grouped by type into ***Urban, Suburban and Rural***.
 
![ridesharing data by type](https://github.com/MarcoFernandez14/PyBer_Analysis/blob/main/analysis/Ridesharing%20data%20by%20type.png)  

* Total rides: the quantity of rides is superior in Uban cities. The ratio Urban : Suburban  : Rural equals to 13:5:1.    
* Total drivers: in the same way than rides, the quantity of drivers significantly is larger in Urban cities. This time the ratio Urban : Suburban  : Rural equals to 31:6:1.   
* Total fares: the total fares are also superior in Urban cities, however, we can observe the ratio Urban : Suburban  : Rural swrinking which indicates that prices differ by type of city. The fares ratio Urban : Suburban  : Rural equals to 9:4:1.
* Average fare per ride and driver: when looking at fares, we can notice that the average fare per ride is higher in Rural cities. Rural cities average fare per ride is 12% higher than in Suburban cities and 41% higher than in Urban cities. Similarly (and even more marked), the average rate per driver in Rural cities is 40% higher than in Suburban cities and 235% higher than in Urban cities.

### Conclusion
We can observe in the chart below that:
- Urban cities generate the most revenue despite having the lowest average fares per ride and per driver
- The access to ride-sharing services and affordability is better in Urban cities than in Suburban and Rural cities.
- The underserved riders in Rural cities use, of course, less the service. However, they are willing to pay higher fares to use the service. 
- The metrics observed remain steady over the period of time observed (January to April).

![fare summary](https://github.com/MarcoFernandez14/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)  

## Summary
In order to address the disparities among the city types, PyBer could:
* Understand if the demand of Rural cities is enough to add more drivers.
* Understand if reducing the price in Rural cities would imply that even less driver will be willing to serve those cities.
* Analyze if there is any kind of seasonality in the data by extending data timeframe. 
* Create a company paid bonus for driver that serve Rural cities in order to increase the attractiveness and therefore the service offer. 
