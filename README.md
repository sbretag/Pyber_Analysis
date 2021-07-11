# Pyber Analysis

## Overview of Pyber Analysis:

V. Isualize, the CEO and co-founder of Pyber, has given us a brand new assignment.  The following has been requested.

1. Create a summary data frame of Pyber stats by city type
2. Create a multi-line graph showing total weekly fares by city type
3. Provide a written summary on hot the data differs by city type and how analysis can aid decision-makers at Pyber

## Resources
- [Ride_Data Source](https://github.com/sbretag/Pyber_Analysis/blob/main/resources/ride_data.csv)
- [City Data Source](https://github.com/sbretag/Pyber_Analysis/blob/main/resources/city_data.csv)
- [Pyber Analysis Code](https://github.com/sbretag/Pyber_Analysis/blob/main/PyBer_Challenge.ipynb)
- Software: Jupyter Lab, Python 3.8.8
- Data Libraries: Pandas & Matplotlib

## Results

### Summary by City Type

![](https://github.com/sbretag/Pyber_Analysis/blob/main/Analysis/pyber_summary_by_citytype.png)
- Rural cities have a siginificantly less amount of rides and drivers than the other two city types resulting in lowering overall fare $ however on a per ride or per driver basis, they have significantly higher amounts at $34.62 and $55.49 respectively.  Assuming rates per mile are charged equally amongst the city types, a reasonable explanation is that drivers are going longer didstances for each fare due to being rural.  Futher testing would need to be performed on miles driven to confirm.
- Suburban cities have a higher amount of rides and drivers than rural, however they are less than urban city types.  Total fares, avg fare per ride, and avg fare per driver are also lower than rural city type but higher than urban type cities.
- Urban cities have a significantly higher amount of rides and drivers than the other two city types resulting in a higher amount of total fares.  On the flip side, avg fare per ride and driver are the lowest amongst the three city types.  It's also important to point out that total drivers exceed total rides which suggests some drivers are not providing any rides at all.



### Fares by Week & City Type

![](https://github.com/sbretag/Pyber_Analysis/blob/main/Analysis/Pyber_fare_summary.png)

- Urban and suburban city types see an increase in fares in early January while rural city types see decrease.  This could be potentially related to weather however further analysis would have to be done to confirm.
- All three city types see an increase in fares from the 3rd to 4th week in February.
- Suburban city types see a large increase in fares from the 2nd week in april though the balance of month while rural and urban city types see a slightly decline over the same time frame.


