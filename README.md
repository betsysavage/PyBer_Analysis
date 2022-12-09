# PyBerAnalysis

## Overview of the analysis

PyBer leadership has requested an analysis of trips, drivers, and fares from their rideshare data by market type. The goal of this analysis is to discover rideshare patterns in the markets of different city types in order to better understand gaps in access and affordability between markets. The analysis is based on Pyber's csv files of city data and ride data.

## Results
To complete this analysis, we merged the two csv files into a single data frame, then grouped the data by city types to target our review by markets. Using the sum and count functions, we created variables to capture summary statistics for total/average rides, drivers, and fares for each market. The summary data frame containing these variables appears below.

<img width="642" alt="image" src="https://user-images.githubusercontent.com/114873837/206607411-d4ced616-19e7-4138-bee6-957e7abc5258.png">

The urban market clearly tops the list in terms of fares collected, number of rides, and number of drivers. However, the volume of riders and drivers tends to keep average fares lower than other markets. Conversely, because there are so few drivers in rural areas, the average fare amount is quite high, which would be quite lucrative for those considering becoming drivers in these more underserved areas.

The next step in the analysis was to regroup the data to describe the total fare amounts by week for each city type. The results were then filtered to a specific date range from January to April. We could then use this newly grouped and filtered data frame to create a line chart comparing the trends in fare amounts over time. The multiple line chart is below:

<img width="1070" alt="image" src="https://user-images.githubusercontent.com/114873837/206607332-56f9a63b-ecd7-4758-8424-65b62f5001cc.png">

Again, it is clear from this visual how drastically the fares vary between urban and rural markets. Suburban areas consistently fall in the middle of the two. Fare amounts remain fairly steady throughout the date range for all markets - There are no wild variations in fares from month to month that would result in a change of rankings between markets. 

## Summary
From the patterns in ride sharing revenue revealed in the analysis, I recommend that the company leverage this information in the following ways:
1. The urban market performs best in terms of overall revenue and the number of ride-sharing drivers the comapny is able to attract. The company should continue to invest in growth in new urban markets, as it will continue to produce a majority of the company's revenue portfolio. However, the question of whether ridership is accessible and affordable in these urban areas is clear - Cities have plenty of options for riders to access a car at a low cost.
2. The rural market brings in the lowest revenue in overall fares. While that trend may make it easier to ignore rural areas in favor of more profitable business areas, we know that leadership is also concerned with access and affordability. From the summary table, the average fare per driver is significantly higher than that of urban drivers. It is likely that riders feel more pressure to accept these fare prices due to lower availability of public transportation as compared to their city counterparts. Would more drivers result in more rides being scheduled, thus lowering the average fare? It is difficult to know the answer until more market research is conducted to assess the demand. 
4. From a data collection perspective, there are a few factors not included in this analysis that may be worthwhile to examine further. For example, how do the average distances of the trips vary between markets, and how might that impact the fare? How many rides does each driver average per year? In addition, would it be helpful to see a full year of data, in case there are any cyclical patterns to ridership for the different markets? I would advise Pyber leadership to consider these research questions for future analysis.
