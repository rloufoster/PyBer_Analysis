# PyBer_Analysis


Exploratory analysis of the ride-share data from January to early May of 2019 along with visualizations.


## Overview

The purpose of this exploratory analysis is to provide Pyber leadership with the insights needed to improve access and affordability to Pyber ride-sharing services for three types of neighborhoods: Urban, Suburban and Rural. This was done by utilizing Pandas Libraries, Jupyter Notebooks and Matplotlib to deliver both descriptive statistics and visualizations that summarize and reflect how the fare data differs by city type for the dates of 01/01/19 through April 28, 2019, and how those differences can be used by PyBer in future decision making.

## Methodolgy

Jupyter Notebooks, Pandas Libraries and Matplotlib were used to perform quantitative analysis and create visualizations.

### Resources

1. Raw Data to Load:  city_data.csv and ride_data.csv

![Files to Load](https://raw.githubusercontent.com/rloufoster/PyBer_Analysis/7d41037046720888b1c4e24317f8adf5605c55e6/analysis/Files_to_load.png)

2. Data to Read: 

![Files to Read](https://raw.githubusercontent.com/rloufoster/PyBer_Analysis/7d41037046720888b1c4e24317f8adf5605c55e6/analysis/Files_to_read.png)

3. Merging DataFrames:

![Merging DataFrames](https://raw.githubusercontent.com/rloufoster/PyBer_Analysis/7d41037046720888b1c4e24317f8adf5605c55e6/analysis/Merge_the_DataFrames.png)



## Results

As depicted by the Total Fare by City Type chart below, the Urban fares are substantially more than the Suburban and Rural neighborhoods respectively. However the seasonal trends tend to be similar across categories.  

![Total Fare by City Type](/analysis/Challenge_fare_summary.png)

-As to be expected, the Urban ride-share volume (Total Rides) is almost 3 times that of the Suburban and 13 times that of the Rural neighborhoods.
-Total drivers in the Urban category is almost 5 times that of Suburban and over 30 times that of the Rural. Total fares for Urban is approximately twice what the Suburban Total Fare and 5.5 times that of the Rural Toal Fares.
-The Total Fares is twice that of the suburban neighborhoods and roughly 8 times that of the Rural.
-The Average Fare per Ride for the Urban category is $10.00 more than the Suburban and $5.00 more than the Urban.
-However, the Average Fare per Driver for the Rural is 
almost $40.00 more than that of the Urban and approximately $15.00 more than the Suburban category.  

![Ride-sharing Data Summary](https://raw.githubusercontent.com/rloufoster/PyBer_Analysis/9ea80d8c975f2603b04420e368e48a449bb5d7b7
/analysis/Challenge_pyberdata_summary.png)  


## Conclusion
 
### Problems

The missing data and resulting NaN's were a challenge and leaves us with an incomplete story.  My first concern, is why is there so much missing data in a system that is automated and tracked? 

### Next Steps

1. First, I would like to propose that an internal audit be conducted to investigate more thorough and dependable tracking.  No form of analysis is going to be effective without the complete data representation. 

2. Secondly, I suggest that we run a fullscale analysis on for the complete year.  With more data points the incomplete data will be less relevant.  This  would also be helpful in determining how much of a seasonal effect this is across the categories (i.e., sporting events in the city, music festivals/concerts, holiday events).

3. And finally, I would like to do some deeper analysis on the effects of different variables on volume across the categories (i.e., Regression Analyses) to identify what is driving the volume.  Pyber could become more reactive about rate adjustments for busier and less busy periods.  We could also use this information to initiate rewards or incentive packages for customers depending upon volume and needs per neighborhood.

