# Surfs_up
## Overview
This is a weather analysis trying to determine the weather impact on investing in a surf & shake shop in the island of Hawaii
### Background
This ana;ysis uses weather data from an SQLite dataset provided by the primary investor in the project, and uses SQLAlchemy with Jupyter notebook for the analysis.
### Purpose
The purpose of this analysis is to show the difference between the weather statistics for the months of June and December in the island of Hawaii, to further investigate the weather impact on the surf & shakes shop investment.
## Results
this part of the analysis focuses on the months of June & December to show the temperature variation in Summer & winter.

1. The analysis statistics for the month of June are as follows:
<img width="224" alt="June" src="https://user-images.githubusercontent.com/79733383/116792590-97dfbd80-aa8f-11eb-95f1-91ef7f13af2a.PNG">

And the histogram for the June statistics as follows:

<img width="563" alt="JuneFig" src="https://user-images.githubusercontent.com/79733383/116792850-3ae50700-aa91-11eb-96f0-be82bdd800d7.PNG">

Both the table & the figure tell us the following:
   1. This dataset has 1700 readings for the month of June
   2. The range of temperatures for these readings are between 64F & 85F, where the average June temperature is 74F
   3. The temperature distribution for June across the dataset is not uniform, also if we apply the interquartile functions on the temperatures, we will find that both the maximum & minimum temperatures lie in the upper & lower outliers zones of the data.
2. The analysis statistics for December as as follows:

<img width="241" alt="December" src="https://user-images.githubusercontent.com/79733383/116793101-ad0a1b80-aa92-11eb-9eb2-57a6c39344f8.PNG">

<img width="584" alt="DecFig" src="https://user-images.githubusercontent.com/79733383/116793114-bb583780-aa92-11eb-835c-090d948b9da9.PNG">

Both the table & the figure tell us the following:
   1. This dataset has 1517 readings for the month of December
   2. The range of temperatures for these readings are between 56F & 83F, where the average December temperature is 71.04F
   3. The temperature distribution for December across the dataset is also not uniform, and applying the interquartile functions shows that both the maximum & minimum readings are in the upper & lower outlier ranges
## Summary 
The analysis made on the months of June & December show that although the temperature variation across both months is relatively low, it is still not completely uniform.

To be able to make a more informed decision, we could try the following:
1. Make a similar study using the precipitation values for both months as well as temperature, to show the rain statistics
2. take a closer look at the outliers of teh dataset & determine their occurance rate 
