# Ride-Sharing Data Analysis
## Overview
The objective of this project is to analyze the ride-sharing data from the Python-based ride-sharing company. We will look for the relationships between the type of the city and the number of drivers and riders as well as the total fares and the fares per ride and driver for each city type. First, the average fare per ride and driver for each city type is calculated and then the total weekly fare for each city type is plotted.
## Data Analysis
### Data Evaluation  
The city data and ride data are read and merged as shown in the table below  

![image](https://user-images.githubusercontent.com/103223944/167212017-73fbbcd6-fa81-4f8a-a566-2ffa38174e14.png)


### Average Fare for Each City Type
Average fare per ride and per driver are calculated based on the total rides, total number of drivers and total fares for each city type as shown below. 
 
![image](https://user-images.githubusercontent.com/103223944/167212034-34011dcd-2458-4c7c-8a7c-00e11a936d6a.png)

### Total Weekly Fare for Each City Type 
The data is grouped based on the city type and the ride date and then total fares are calculated for each date. Then, pivot table is used to re-arrange the data such that the total fare for each date and the city type is presented. Then, the data is resampled to represent the weekly total fare for each city type and finally, the data is plotted using the fivethirtyeight style as shown below. 
 
![image](https://user-images.githubusercontent.com/103223944/167212058-ad56ebcb-441c-4484-a85d-77e57eb2baa8.png)

## Summary 
The total number of drivers and rides are larger in the urban areas most likely because the larger investments have been made by the company in those areas to hire more drivers. The larger number of drivers provide better ridesharing accessibility which in turn results in more affordable ride prices compared to the rural/suburban areas. Therefore, it’s suggested to hire more drivers in the rural areas to provide better accessibility and more affordability which will lead to larger revenue for the company. The second priority would be to hire more drivers in the suburban areas. 
