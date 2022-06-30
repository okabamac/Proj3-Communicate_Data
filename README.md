# Diamonds Data Exploration

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. It includes information for columns such as; 'duration_sec', 'start_time', 'end_time', 'start_station_id','start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name',   'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip'. 
Outliers, null values, and data types all required to be modified. To analyze and visualize the data, I utilized Python and its tools such as pandas, numpy, matplotlib, and seaborn.

The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv.),
with feature documentation available and additional data found [here](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems).


## Summary of Findings

The typical duration of riders is between 25 and 40 years old, and also most journeys last between 2 and 12 minutes. Many trips occur on work days, and the most typical hours for individuals to ride bikes are between 8 am and 5 pm Male cyclists outnumber females. From the age of 20 to the age of 40, the journey duration ranges from 2 to 40 minutes, and it reduces when the age of the subscribers exceeds the age of the clients.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the duration and age of riders
and leave out most of the intermediate derivations. I start by introducing the
duration variable, followed by the pattern or relationsship with other variables using barplots and scatterplot

The relationship between age and the duration per user type was not obvious, therefore I had to separate each user type into its own chart to better observe the difference.
