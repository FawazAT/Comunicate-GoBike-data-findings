# Ford GoBike System Data
## by Fawaz AlTuwaijri


## Dataset

The dataset has informations about Bay Wheels's trips. Which is a biking rental information. It has around 177,000 records, including:  
* duration_sec
* start_time
* end_time
* start_station_id
* start_station_name
* start_station_latitude
* start_station_longitude
* end_station_id
* end_station_name
* end_station_latitude
* end_station_longitude
* bike_id
* user_type (“Subscriber” = Member or “Customer” = Casual)
* rental_access_method


## Summary of Findings

In the wxploration, I found that there was no strong relationships between the duration of a trip and other attributes. Although with deeper investigations I fount that Normal customers tend to have slightly longer durations than subscribers, except when the starting station ID is 30. Also customers who use clippers tend to have a variaty in durations more than others.

## Key Insights for Presentation

For the presentation, I focused on just the influence of the User type and station. I started by introducing the duration variable, followed by the Duration and User type relation, Then finished by showing The relation between the Duration and User type with start station. 
There is no clear relation between the duration and other attributes. There is slightly higher trip duration when the User type is customer.
The second and thierd graph will address that, There are some stations where the subscribers tend to have some above average rides longer than customers.