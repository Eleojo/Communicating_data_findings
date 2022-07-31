# (Communicating Data Findings)
## by (Eleojo E. Adegbe )


## Dataset

> This dataset contains 183412 instances of trips around San Francisco Bay area, with 16 feature variables which includes duration for trip and start and end time of trips.This dataset contains instances of trips just for the month of february 2019.


## Preliminary Wrangling
> Dropped null values in start_station_id, start_station_name, end_station_id, end_station_name, member_birth_year and member_gender as there was no way of getting these data.
> Changed member_birth_year should be int.
> Changed Start and End times toin datetime format.
> changed user_type,member_gender and  bike_share_for_all_trip to categorical.
> Created new columns for day of the week and time of the day.
> Converted duration_sec variable to minutes.
> Converted member_birth_year to actual user age.

## Summary of Findings

> The group that brings more revenue to the company are Male Subscribers 20-40 years old that dont use the bike_share_for_all service
> The group that generates the least income are poeple of the "other" gender that are Subscriber type that patronise the bike_share_for_all service.
> The Subscriber type users have the most numbers but the customer type spend more time riding (an average of about 20mins compared to about 10mins of Subscriber type)

## Key Insights for Presentation

> Total count distribution for categorical variables.
> Riding duration for categorical variables

