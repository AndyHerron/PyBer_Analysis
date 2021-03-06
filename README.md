# PyBer Analysis

## Overview of analysis
We have been provided with two sets of data on drivers in different cities.  Using Python and Pandas, we were tasked with creating a variety of reports to present to the PyBer company leadership.
The analysis will help PyBer improve access to ridesharing services and determine affordability for different types of cities.


### Resources
* Data Source: city_data.csv and ride_data.csv
* Software: Python 3.8.8, Jupyter Notebook


## Results

![PyBer summary dataframe](https://github.com/AndyHerron/PyBer_Analysis/blob/main/Resources/PyBer_summary_df.png)
### Describe the differences between different city types.
The data was collected for a wide range of cities and broadly grouped into three categories - Rural, Suburban and Urban.  These categories were chosen based upon the city's population size.

### Describe the differences in total rides, total drivers and total fares by city type.
The number of total rides increased with each larger city type. The number of total rides for Urban cities was more than 2.5 times larger than that of Suburban cities, and 13 times larger than Rural cities.  
There are also correspondingly more drivers in the larger cities.  With significantly more drivers and more total rides, it is not surprising that the total income (fares) was much higher for Urban cities.

### Describe the differences in average fare by ride, and average fare by driver by city type.
The size of the cities has an opposite effect on the average fare per ride.  Urban cities had the smallest average fare per ride, and Rural cities the largest.  Perhaps this is due to shorter trips in Urban settings.
Rural areas tend to be more spread out, so the average length of the rides is longer, which results in a higher average fare in those areas.  Rural cities also had a higher average fare per driver than
Urban and Suburban cities.

![PyBer weekly fares](https://github.com/AndyHerron/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
## Challenge Summary
On the surface, these results seem to make sense.  Urban cities have higher populations, which means a higher number of potential customers.  Those Urban customers utilize PyBer's ridesharing services in much higher numbers than
Suburban or Rural people do, and with the much higher number of rides it makes sense that the total income (fares) for Urban areas represents the lion's share of the overall income.  What is perhaps not as obvious on the surface
is the fact that Suburban and Rural areas are more profitable per ride than in Urban areas, and that the drivers in those areas earn more per ride.

### business recommendation #1
Rural cities have the largest average fare per ride. The rides in Rural cities provide the highest amount of income per ride, so increasing the number of rides in those areas would potentially be the fastest way to increase the
overall income for the company.  

### business recommendation #2
Suburban areas have more rides than drivers. Rural areas also have the lowest number of drivers available to provide service.  Recruiting more drivers for these areas seems like a great avenue for growth.

### business recommendation #3
Urban cities have more drivers than rides. That means that some of the drivers in Urban cities are not actually working.  There is a surplus of drivers in Urban areas and there isn't enough work to keep them all busy.  
Furthermore, the average fare per driver is significantly less than Rural or Suburban areas, so the Urban drivers are not earning as much for the rides they do provide.  If possible, shifting some of the Urban drivers 
to Suburban or Rural areas would balance out the number of drivers with the demand for rides.
