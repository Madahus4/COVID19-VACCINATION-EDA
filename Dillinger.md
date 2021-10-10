
## ANALYSIS Of MTA Turnstile data New York CITY
The goal of this project is to provide people with vaccination centers and provide enough space in each station.

<img src ="https://github.com/Madahus4/EDA_Project/blob/main/totaltrafficBassedOnDays.png"
alt ="drawing" width="600"/>

To start exploring this goal, I used a bar plot to determine which stations will make it to our final recommendations.

In the above graph we plot the daily total traffic of all stations combined from Sep to Dec. There is a clear periodicity. It is reasonable to assume that traffic goes up on weekdays and reduces on weekends.

In this section we visualized the traffic of the busiest station in New York by hour and day of week. Our first step is to resample the data by 4-hour time intervals and round the timestamps to 0/4/8/16/20 o'clock. Resampling and rounding is necessary because in the original data, records are generated at irregular timestamps when a gate shuts down for maintenance or runs into other issues.
