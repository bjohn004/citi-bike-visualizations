# citi-bike-visualizations
An Analysis of citi bike data from 2017 to 2022 utilizing Pandas and Tableau.
## Data Exploration and Cleanup
***
All of the CSVs from the year 2021 were downloaded and brought into Pandas as their respective dataframes. The month of January required some cleanup to rename columsn since CitiBike has changed their data column headings as of February 2021.

There are approximately 27,000,000 records of data in the year 2021, so the jupytner notebook utilizied a filter to find the top 10 most popular start stations. This was completed by finding the starting stations with greater than 95,000 occurences in the year.

This CSV gets reduced down to about 3,000,000 rows and will be exported to use in Tableau for Visualization Purposes
## Tableau Presentation
The presentation is digging into two observations.

1. The top 10 stations and how they space out around Manhattan and how they fair in terms of different months during 2021. Slides 1 to 6 outlined below help visualize this observations.

1. The difference between members of CitiBike and casual users. Is there a difference that can be seen from different times of the year and different parts of the City. Slides 7 to 8 outlined below help visualize this observations.

1. The additional slides of the map with zip codes helps show the more used station in relation to these zipe code boundaries.

***
**Slide 1**
- This slide shows the locations of the Top 10 Most Popular CitiBike stations to help give a frame of reference.

**Slide 2**
- This Horizontal bar chart demonstrates the highest visited End Station generated from the top 10 Starting Stations. 

- Analysis: Many of the stations in the top 10 list of starting stations are also towards the top of this bar chart which indicates a lot of short rides may be happening or its often common for people to return bikes to the place they started. These people could be members of CitiBike who use the bike for short trips around the Cityh.

**Slide 3**
- The bar charts demonstrate the total trip distance and total duration of the trips that the Top 10 Stations cumulated each month.

- Analysis: The trip durations and distance of trips indicate that there is generally more bike riding occurring in the summer months. Additionally the casual riders' time spent on the bikes tends to increase at a higher rate in the summer months indicating that tourists/casuals are more likely to ride in the summer or that their are more tourists in the summer in general.

**Slide 4**
- The bar charts demonstrates the percentage of rides that utilized the different bike types by Month.

- Analysis: No data was calculated in January as January was still using the previous data collection system. The docked_bike appears to occurr 100% of the time from February to May indicating that the City either permanently is swapping out the docked_bikes or they swap them for Winter months. However it seems that in December of 2021 there are very little docked_bikes, so it seems the classic_bike and electric_bike are being utilized now.

**Slide 5**
- The dashbaord demonstrates top 5 start stations and the percent of the rides that are by members of CitiBike or casual users.

- Analysis: This chart demonstrates which top stations are likley more subscriber driven or touristy driven. The most popular startions with a higher proportion of casuals occur along the south/west part of Manhattan. This indicates the review of needing enough hotels and other touristy features within these parts of the City. T

**Slide 6**
- Map that shows the most frequently visited end stations by the size of the circle and it runs through the top start stations as the unique identifier for the map.

- Analysis: the map shows that most of the start stations are located on the southern part of the island. the 1 Ave and E 68th Street Station appears to be the most popular station on the northern middle half of the island. This station also has the most frequent connections with Brooklyn compared to the other top 10 stations.

**Slide 7**
- This second dashboard helps us understand the difference between members of CitiBike and casual users.

- Analysis: As seen in the top chart, the total users increase in the summer months. The bottom chart helps show the demand of CitiBikes and the top 10 stations from the first analsyis.

**Slide 8**
- The bar chart showing the difference in average trip distance for casuals or members and by the type of bike they are riding.

- Analysis: the average disance difference between casuals and members is generally consistent with the different bike types. Casuals generally have longer bike rides and e-bikes are usually used for longer trips. Casuals are more likely to be tourists and go on longer rides, so can we find a way to get more E-Bikes in the tourist heavy bike areas?

**Slide 9**
- The map is isplaying the zip code boundaries in addition to the most frequent Start Stations. The average duration of these rides are also indicated by the color of the ciricle. So larger circles are end stations that have a more frequent starting stations, and the color shows longer trips the closer the color gets to green.

