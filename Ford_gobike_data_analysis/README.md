# Ford gobike Data Analysis
## Babatunde Olaniyi


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in the United States of America.

There are 183412 fordgobike trips in the dataset with 16 specifications (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). Out of 16 specifications 9 are numerical, 2 are datetime, 4 are object type and 1 is boolean type. New columns were created out of the original 16 to create new features such as start_hour, end_hour, distance_km, start_day and end_day. 


The data wrangling and exploration process took me through the conversion of data types and and feature engineering by  creating new column  ease the analysis process. I was able to also split out the hour from the time stamp of the start_time column which made it possible for me to eplore and visualize the hour of the day with most bike trips. 



## Summary of Findings

In the exploration, I found that there is a strong relationship between the gender of bike riders and the duration of bike rides. There is a higher percentage of female and other gender doing longer trips. I was also able to discover that bike trips are most likely to start towards the evening.
It was observed that though the number of higher duration trip is higher for male but percentage is higher for women and other, also other gender has one more peak at nearly the age of 60 years for higher duration time. For different user types both are showing similer trends for age and trip duration. But there is slight tilt to higher age for subscribers having better trip duration.

## Key Insights for Presentation

For the presentation, the key insights in focus include the distribution of bike ID's which gives an insight into the most commonly used bikes. I also focused on the hours of bike trip start_time by splitting out the hours from each time stamp in order to visualize the distribution of start times and also give insights into the hours of each day with most bike trips.

I started by presenting a visualization of bike ID's and distribution of bike trip start hours. I also shared insights from the multivariate visualization of the relationship between age, gender and bike trip duration.