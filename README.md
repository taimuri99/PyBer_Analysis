# PyBer Analysis
Module 4 Jupyter Notebook &amp; MatPlotLib: PyBer Ride-Sharing Analysis
## Overview of the analysis
PyBer, a ride sharing app has asked us to analyze and visualise ride and driver data for different cities. We did this by analyzing drivers and rides for different city types:

1) Urban
2) Suburban
3) Rural

The aim of the module was to see visually how being in a different city type affects ride fares, driver count and ride count. For the challenge, we are asked to show visually how total fares of different city types behave on a weekly basis in addition to a summary dataframe of the ride-sharing data by city type. 
## Results
Here are some of the results found after analyzing and visualising the data.
### Summary DataFrame

<img width="594" alt="SummaryDF" src="https://user-images.githubusercontent.com/87828174/135165891-c4c0706c-8d1f-4104-b7f6-e67dc5def6f3.png">

In the summary created above, one can see the total drivers, rides and fares as well as the average fare per rider and per driver. Some noticeable key points are:

1) Total number of rides are largest for the urban city type while the smallest number are in the rural city types.
2) Total number of drivers are largest for the urban city type while the smallest number are in the rural city types.
3) Total fares collected are largest for the urban city type while the smallest number are in the rural city types.
4) Average fare per ride is highest for rural city type while being lowest for urban city type.
5) Average fare per driver is highest for rural city type while being lowest for urban city type.

One can see that due to the number of drivers and rides in rural areas being much less in comparison to other city types, the average fare per driver and ride is much higher than suburban and urban cities. One of the reasons for this is that urban cities are highly populated and have more available resources as cars or drivers as opposed to rural areas which have low populations and infrastructure. Although the total fares are also less for rural types, the stark difference in amount of rides booked or drivers available compared to urban and suburban cities, cause the averages to decrease. Suburban city types are in the middle of the two extremes as expected as they're not as densely populated as urban cities therefore less amounts of drivers and rides, yet are more populated than rural areas which are scarcely populated.  

#### Ride Sharing Data Visualised
Here is visual aid to help better understand the distribution of average fare vs total number of rides per city:

<img width="950" alt="PyberRideSharingData" src="https://user-images.githubusercontent.com/87828174/135173592-6f9a737b-c082-4b5a-9d16-dcad3fd493af.png">

Noticeable key points:

1) As total number of rides per city increases, the bubble chart becomes more densely populated by urban city type while the rural city type is more prominent in lower rides per city due to density of populations and infrastructure.
2) As the average fare increases, the plot is more densely populated with rural areas due to the reasons listed above: Less population therefore less infratructure, cars, drivers and rides therefore causing the average fare to increase. 
3) Simlarly average cost per ride decreases in suburban to urban areas due to access to larger number of drivers and therefore more rides.
4) The bubble size depends on the driver count per city which matches our analysis. On average, largest counts or bubbles for urban areas and smallest counts for rural areas. 

#### Box Plots
The following three box plots further explores our analysis of city types:

<img width="648" alt="DriverCountData" src="https://user-images.githubusercontent.com/87828174/135174943-eed33b6b-c722-44e2-aa5c-c46647061a24.png">
<img width="625" alt="RideCountData" src="https://user-images.githubusercontent.com/87828174/135174962-de972d86-42e5-4499-8bc0-3db23ceecb47.png">
<img width="633" alt="RideFareData" src="https://user-images.githubusercontent.com/87828174/135174975-9e83458f-fe2d-4bc4-9b60-8651ae9551d9.png">

These plots match our analysis showing:

1) Higher range and mean number of drivers and rides for urban areas.
2) Lowest range and mean number of drivers and rides for rural areas.
3) Suburban driver count and ride count between the two extremes.
4) Highest range and mean fare for rural areas.
5) Lowest range and mean fare for urban areas.
6) Suburban mean fare between the two extremes.

One thing to notice from the box plots and the bubble chart, values for average fare, driver count and ride count tend to overlap between cities of the three types but on average they follow a trend:

1) For driver and rides count: Urban Count > Suburban Count > Rural Count
2) For mean fare: Rural Mean Fare > Suburban Mean Fare > Urban Mean Fare

#### Pie Charts
Lastly two pie charts visualise the shares of rides and drivers for all three city types:

<img width="407" alt="%RidesCityType" src="https://user-images.githubusercontent.com/87828174/135175744-49e1dfcb-3429-4ef3-b813-fa0d8fedd078.png">
<img width="442" alt="%DriversCityType" src="https://user-images.githubusercontent.com/87828174/135175746-482b4350-0e1a-43a4-9319-84bf13181c90.png">

### Multiple Line Chart

![PyBer_fare_summary](https://user-images.githubusercontent.com/87828174/135175791-f4ae4909-d4c8-49df-8516-468a685ca0ac.png)

Above is a multiple-line chart of total fares for each city type. Some key points taken from this visualised data is:

1) 


## Summary
