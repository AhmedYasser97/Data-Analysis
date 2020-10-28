# Ford GoBike System Data
## by Ahmed Yasser Mostafa


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the San Francisco Bay area in 2017. This includes the duration of the ride, location of start and destination points and their start and end times.

#### Changes done to the dataset during the exploratory part:

1. Create a column for duration in minutes (duration_min) by dividing the duration_sec by 60
2. Create a column for duration in hours (duration_hour) by dividing the duration_min by 60
3. Deleting the rows with duration (in hours) that are greater than or equal to 6 hours
3. Extract the month from start_time in a separate column
4. Create a column for distance in kilometers, based on the longitude and latitude start and end points (feature engineering)


## Summary of Findings

1. In 2018, the average trip duration that the users took was from 5 to 50 minutes and rarely exceeded 60 minutes.

2. The number of rides are much higher in August till December than other the months (keep in mind that the dataset includes rides from June till the end of the year only).

3. There was no significant difference between the months and the trip duration.

4. The Customers usually on average took more time in their rides than Subscribers. Only in June, it showed that subscribers take longer rides.

## Key Insights for Presentation

F## Key Insights for Presentation

For the presentation, I focus on just the influence of the user type, month of the ride on the duration of the ride. The distance between the two stations (which was feature engineered) hasn't proven to be significant in the findings. I start by introducing the duration (in minutes) variable (which was also feature engineered).

Afterwards, I introduce each of the variables that might affect the duration such as the user types and the month of the ride and I display their respective histograms. 
Then, I show how much each user type takes on average in their rides on average using a bar plot. Finally, I factor in the month variable by seeing if it affected the same duration for each user type.