# Surf and Shake Shop Analysis

## Overview
### Purpose
Potential investors in a new Surf and Shake Shop are concerned about the impact weather may have on the success of the business. This analysis was undertaken to learn more about temperature trends between the summer and winter months and to determine if the Surf and Shake Shop is a sustainable year-round business idea.

## Analysis
Temperature data for the months of June and December were extract from the data set, summarized, and compared using Python, Pandas, and SQLAlchemy.

## Results
| ![June Temps](/Tables/JuneTemps.png)|![December Temps](/Tables/DecemberTemps.png)
|:--:|:--:|
|*Summary statistics of June temperature data.*|*Summary statistics of December temperature data.*|

* The mean temperature in June was approximately 4 degrees higher than December, 74.9 and 71.1, respectively.
* The range of temperatures (difference between minimum and maximum temperature) is larger in December (27 degrees) than in June (21 degrees).
* While the range of temperatures is larger for December, the standard deviation is lower indicating that data is more clustered around the mean. In other words, the temperature is slightly more stable/reliable in December than it is in June.
* There were approximately 200 more data points for June than for December.

## Summary
Looking solely at temperature data from June and December, there is no reason to believe that the Surf and Shake Shop would not be a sustainable, year-round venture. The difference in temperature between June and December is only 4 degrees and the mean temperatures for both months is in the 70s - plenty warm for surfing and ice cream.

### Additional Queries
Weather conditions that may impact business at the Surf and Shake Shop goes far beyond temperature. In particular, precipitation and wind could create conditions that deter individuals from visiting the shop. Additional queries should be run to analyze these weather parameters as well. 

To maximize the success of Surf and Shake Shop, queries comparing weather patterns between stations should be used to narrow down optimal locations for the business on the island. 
