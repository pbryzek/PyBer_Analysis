# Bootcamp: UCB-VIRT-DATA-PT-03-2020-U-B-TTH
### Bootcamp Challenge #5 - 4/12/2020
Bootcamp Challenge 5: PyBer_Analysis

### Resources
- [CityData](https://courses.bootcampspot.com/courses/140/files/36435)
- [RideData](https://courses.bootcampspot.com/courses/140/files/36482)
- Software: Python 3.8.2, Visual Studio Code, 1.43.2

### Excel Python Script
- [PyBer_Challenge](PyBer_Challenge.ipynb)
- [PyBer Analysis](analysis/fare_sum_city_type.png)

## Challenge Overview
The goals for this challenge are for you to:
    Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
    Use Pandas methods and attributes on a DataFrame or Series.
    Create a new DataFrame from multiple groupby() Series.
    Format columns of a DataFrame.
    Create a multiple-line graph.
    Annotate and apply styling to the chart.
    
## Challenge Data Analysis and Summary
### Summary DataFrame Analysis
The summary dataframe presents us with Total Rides, Drivers, and Fares segmented by Urban, Suburban, and Rural City Types. We can see establish clear patterns across the City Types. The total rides display a ratio of 1:5:13 across Rural, Suburban, and Urban City Types respectively. Total Drivers ratio was, 1:6.3:30.8. Total Fares 1:4.47:9.2. These numbers clearly show that Urban areas was the city type that demonstrated the most total rides, drivers, and total fares. We see that Urban cities accounted for 13 times the total rides, nearly 31 times as many drivers, and ultimately over 9 times more fares earned than rural cities. Suburban cities logically fell inbetween Urban and Rural showing higher numbers in each category than Rural cities but less than those of Urban Cities. 

The data for Average Fare per Ride and Average Fare per Driver demonstrated the opposite pattern - for each category Rural cities had the highest values while Urban demonstrated the lowest. Ratios of average fare per ride was 1: 1.26: 1.4 for Urban, Suburban, and Rural cities. Ratios of Average Fare per driver was 1: 2.4: 3.3. We can observe a clear pattern - rural cities have higher average fares per ride and fares per driver than Urban and Suburban cities we may infer that this could be due to longer travel distances on average in rural areas. 

As Urban cities tend to be denser in population and city services than Suburban cities, which are denser than Rural cities, we can observe a pattern that PyBer tends to be more widely used in denser cities, supporting more rides, drivers, and ultimately total fares. 

### Multiple Line Graph Analysis
Tells you about the fares for each city type over time.
