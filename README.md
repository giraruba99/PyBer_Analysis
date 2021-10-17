# PyBer_Analysis
* In this PyBer analysis, we are digging into thousands of data collected by a ride sharing company, and we are anlyzing the data in Urban, Suburban and Rural cities. 
## Purpose: The main purpose of the analysis could be summarized as:-
   * To find the total number of rides per city type(Urban, Suburban and rural cities).
   * To find the total number of drivers per city type.
   * To find the total amount of fares per city type.
   * To average the fares per driver and per rides per city type.
   * To analyze the data by taking a snap-shot of January-April time period.
   * To analyze the data on weekly bases and show the sum of fares each week.
   * T present a visual plot graph that clearly shows the total fares per city type.

## Result and Analysis:
 ### Results per city type:-
 * Urban Cities: As we may have expected urban cities got the highest number of drivers, total rides and total fares. But, due to short distances per each trip, average fare per ride is the lowest in urban cities. And offcourse, each driver gets the lowest average fare compared to other city types.
* Suburban cities: Suburban cities got results in between Urban and Rural cities. The total rides, drivers and total fares are more than of th Rural cities, but much lower than Urban cities. On the other side though, average fares per ride and average fares per driver are more than of Urban cities, but lower than Rural cities.
* Rural cities: Rural cities are less dense, thus they tend to have less number of fares, few drivers and low amount fare totals. But, since each trip is usually long, the average fare per ride and average fare per driver is vsisbly higher than Urban and Suburban cities.

![Pyber sumarry DataFrame](https://user-images.githubusercontent.com/89214854/137615129-666382e6-69b1-4aaa-af5a-86e8e3f98b04.png)


### Visualization of PyBer results per city type
* The following graph clearly shows fares per city type.

![Challenge_fare_summary](https://user-images.githubusercontent.com/89214854/137615145-d9f18687-4660-4841-9cce-a07337d2303f.png)


## Summary and recomendations
   * Finally, we could summarize the findings as follows:
     - The number of drivers in Rural cities it very low, and customer wait time might be to long
     - There are too many Urban drivers, and the share of each driver from the fare is not great (it can also be due to the distance covered by a trip)
     - Suburban cities looks better in distribution of their data. They probably got enough number of drivers and each driver takes satisfactory amout of money from a trip.
    * Based on the analysis we run, we recommend the ridesharing company to:
      - Hire more drivers in Rural areas to reduce customer wait time.
      - Implement more price surge in urban cities, that way drivers get some more money to keep they business alive.
      - Encourage rural customers to schedule a ride rather than requesting (this will lower customer wait time).
