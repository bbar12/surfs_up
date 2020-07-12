# surfs_up

###Challenge 

In the search for ideal weather and location for a surf and ice cream shop in Oahu, it was both important and informational to have temperature data for different stations throughout the island. The results of this analysis were performed on the 'measurement' database available. 

To be taken into consideration for this analysis is determining whether the location for this business is adequate year round. As a preliminary analysis, the months of June and December were queried in the database for both precipitation and temperature. The goal of this is to obtain mean measurements of temperature at minimum to determine whether the appropriate weather is present in Oahu year round. 

To begin, we can look at the temperature and precipitation trends within the month of June across all available years and stations of data. 

![JuneDataPlot] 

Though it is noted that the temperature remains solidly within the 70F-80F range we can solidify our understanding of the data obtained from the June months. A describe() function is used on the resulting dataframe as shown below:

![JuneDatadescribe]

The mean value for precipitation is 0.14in and mean temperature is 74.9F. We can also see that the minimum (or worst case temperature measurement) is 64F. 
We continue our analysis through the evaluation of the same parameters to obtain a December plot for all available years and stations of data available. 

![DecemberDataPlot]

We see a similar trend of temperature data ranging among the temperature trends of 70F-80F with some instances where the temperature decreases to 60F and slightly below. Once again we can apply the describe() function to obtain key statistics on the month of December for all years. 

![DecemberDatadescribe]

Comparing the 
