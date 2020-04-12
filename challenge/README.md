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
The summary dataframe presents us with Total Rides, Drivers, and Fares segmented by Urban, Suburban, and Rural City Types. We can see observe clear patterns among the City Types. The total rides display a ratio of 1:5:13 across Rural, Suburban, and Urban City Types respectively. Total Drivers ratio was, 1:6.3:30.8. Total Fares 1:4.47:9.2. These numbers clearly show that Urban areas was the city type that demonstrated the most total rides, drivers, and total fares. We see that Urban cities accounted for 13 times the total rides, nearly 31 times as many drivers, and ultimately over 9 times more fares earned than rural cities. Suburban cities logically fell inbetween Urban and Rural showing higher numbers in each category than those of Rural cities but less than those of Urban Cities. 

The data for Average Fare per Ride and Average Fare per Driver demonstrated the opposite pattern - for both categories, Rural cities had the highest values while Urban had the lowest. Ratios of average fare per ride were 1: 1.26: 1.4 for Urban, Suburban, and Rural cities. Ratios of Average Fare per driver were 1: 2.4: 3.3. We can observe a clear pattern - rural cities have higher average fares per ride and fares per driver than those of Urban and Suburban cities. We may infer that this could be due to longer average travel distances in rural areas, resulting in higher fare amounts.

As Urban cities tend to be denser in population and city services than Suburban cities, which are denser than Rural cities, we can observe a pattern that PyBer tends to be more widely used in denser cities, supporting more rides, drivers, and ultimately total fares. 

### Multiple Line Graph Analysis
To complete the second part of this challenge, we had to aggregate the data per City Type which provided a break down of how much money was earned on each fare with respect to Date. We were interested with the time range from 2019-01-01 to 2019-04-28 which is represented in the x-axis. The y-axis represents the sum of the fares for each city type. All three city types: Urban, Suburban, and Rural were plotted on the same chart to allow for comparison over this time period. The data was then segmented into 7 days bins so that a week by week sum of the total fares could be compare among the three city types.

The first trend that is immediately obvious is that the rankings (based on total Fare $USD for that date) do not change throughout the entire period - Urban had higher weekly total fares than Suburban and Rural, Suburban posted higher weekly totals than Rural for every week in this period. It can be see that beginning in Jan 1 2019, Urban, Suburban, and Rural had about $1,600, $700, $250 - clearly indicating that the majority of all fares originated from Urban areas. At the close of the period, these values were approximately $2,200, $1,400, $200. The respective ranges were approximately ($1,600-$2,550), ($650-$1,450), ($50-$500).

As Rural cities had much less volume, we see the highest fluctuations (percentage wise) throughout the months evaluated with peak values 10x from its min value. In Suburban cities there was about a 2x difference in min and max values, urban had the lowest fluctuation of only about 55% from min to max values - but Urban's min weekly was greater than both Suburban and Rural's max daily fare sum. We see that in Rural cities, sometimes there was close to zero total fares earned in that week representing a sometimes close to zero demand. 

For Urban cities, there is a clear positive trends as its min value was the start of the date range, peaking just before  2019-3-1, with the trend correcting itself a bit throughout March, and reaching what may repsent a new level of stability throughout April. 

Suburban cities showed overall positive trends with higher total fares over time indicating total rides are increasing in this city type. 

Rural cities did not indicate an overall growing trend as was seen with Urban and Suburban cities. Rural cities show a pattern of occasional spikes followed by occasional droughts of nearly zero $USD collected. When Rural cities had their peaks for total fares (when looking at its max total per each month), this same time period always showed that Urban cities were not at their max value. As an example, we see Rural cities having a peak around 2/20 for the month of Feb, while Urban's peak for that month was around 2/27. We may infer that the rural cities seek a peak in Pyber usage when the urbanites go to rural cities for a weekend, which would explain why urban cities would not see their peak usage during this time.

We can see that all three city types reached their max value in the month of Februrary, this may indicate that people are more likely to use the services in the month of Februrary, perhaps valentine's day has something to do with this as more couples go out on dates, dinners, and activites in the month of Februrary. 

We can infer that PyBer is becoming more popular in Urban and Suburban cities while it is less frequently used in rural areas, usually from sharp spikes followed by sharp drops in total daily fares. One possible reason to explain the occasional spikes in Rural areas is that they result from Urban and Suburban travelers who visit the rural areas for a weekend or vacation, resulting in an increase in PyBer demand and thus its total daily fare for that brief period. 

A rural driver may want to strategically leave his city type for either suburban or urban cities during the middle of the months where the total fare looks to be lowest, working in the other cities during those periods would likely earn him a better total fare. He could then return to the rural areas during the end of the month "spike periods" to capture a solid total fare as he would be competing with far fewer drivers for a temporarily inflated total fare amount for rural cities.
