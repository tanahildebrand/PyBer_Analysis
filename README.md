# PyBer Ride Share Analysis
## Overview
The purpose of this project was to complete an analysis of PyBer rideshare data from January-May 2019. The raw data included the city, type of city, driver count and fare. Our goal was to create visualizations of the data to present trends and areas of focus.

## Results
#### Fig 1. PyBer Summary
![Pyber Summary](/analysis/Summary_Table.png)

Figure 1 illustrates a simplified summary of the raw data. The number of rides per driver in rural and suburban areas outweights that in the urban cities (rural 1.6 drivers per rider; suburban 1.27; urban 0.7). Though the total revenue is highest in urban areas, the amount incoming per driver is the lowest at $16.57 per driver. The average fare is highest in urban areas, folowed by suburban, and then rural.

#### Fig 2. PyBer Fare Summary by City Type
![Pyber Fare Summary](/analysis/Pyber_fare_summary.png)
Figure 2 illustrates the total fare revnue by month, broken down by the type of city. Overall, the fare revenue remains relatively stable each month based on the type of city, with a slight increase moving toward warmer months. In addition, we can easily see that urban area fare revenue outweighs the rural and suburban cities on a consistent basis.

## Summary
Based on the above analysis, I recommend the following areas for further review:
 - The ratio of drivers to riders in urban areas is lower than the other city types. There are more drivers than there are rides. This might indicate that the urban areas are overstaffed. A review of real-time demand vs. active drivers should be reviewed to determine if there room to reduce staffing. A reduction is staffing could result in reduced costs - both administrative and driver pay. This could also improve staff satisfaction as the average fare per driver would increase, asuming demand remains steady.
  - The average cost per ride is higest in the rural areas, while the number of drivers is also lowest. Both of these factors might disincentivizing those that live in these areas from using the PyBer service as it's expensive and inconvenient (long wait times). Assuming more the services are desired, a strategy to improve this should be developed. One example of an offering could be to offer discounts to the service if the ride is pre-scheduled.
  - The analysis assumes that drivers are exclusive to one city, and do not work across multiple types of cities. Many cities feed into suburban areas and then rural areas, which means the individual rides can span across city tyes (i.e. urban to suburbian). 
