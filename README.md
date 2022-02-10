# Bikesharing

## Overview of the Statistical Analysis

### Purpose:

There is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. For this analysis, I'll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
 - Show the length of time that bikes are checked out for all riders and genders
 - Show the number of bike trips for all riders and genders for each hour of each day of the week
 - Show the number of bike trips for each type of user and gender for each day of the week
Finally, I’ll add these new visualizations to the two I created in this module for my final presentation and analysis to pitch to investors.

## Results:

[link to dashboard](https://public.tableau.com/app/profile/sebastian.scholl/viz/NYC_CitiBike_Challenge_Trip_Analysis_16444545557670/NYCCitibikeStory?publish=yes "link to dashboard")

### Top Starting Locations
![Top_Starting_Locations](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Top_Starting_Locations.PNG)

The most popular places for Citibike customers to begin their journeys in New York City are:
1. Pershing Square
2. Broadway
3. Tribecca Bridge

### Top Ending Locations
![Top_Ending_Locations](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Top_Ending_Locations.PNG)

The most popular places for Citibike customers to end their journeys in New York City are the same as starting locations.

## Checkout Times for Users
![Checkout_Times_for_Users](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Checkout_Times_for_Users.PNG)

Peak usage for NYC Citibikes occurs at 5 minutes.  146,752 bikes were checked out at 5 minutes for August 2019.  33 Citibikes were checked out for at least 2 hours and 59 minutes.


### Checkout Times by Gender
![Checkout_Times_by_Gender](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Checkout_Times_by_Gender.PNG)

Males were the primary user of Citibikes in August 2019.  There were 34,151 female Citibike users at peak usage, which is 68.4% less than male rideres.


### Trips by Weekday
![Trips_by_Weekday](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Trips_by_Weekday.PNG)

Citibikes are used the least between 12 AM and 5 AM Sundays through Saturdays.  This may be a good time for Citibikes to perform maintenance on their bikes.


### Trips by Gender (Weekday per Hour)
![Trips_by_Gender_(Weekday_per_Hour)](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Trips_by_Gender_(Weekday_per_Hour).PNG)

Citibikes are popular amongst males and females around 8 AM, 5 PM, and 6 PM Monday through Friday.  Usage is popular on Saturdays between 9 AM and 7 PM for male and femal riders.  On Sundays, male and female riders appear to use Citibikes the most between 11 AM and 5 PM.


### User Trips by Gender by Weekday
![User_Trips_by_Gender_by_Weekday](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/User_Trips_by_Gender_by_Weekday.PNG)

In August 2019, Thursdays are the most popular days to use Citibikes amongst male and female subscribers.  Sundays were the most popular days to use Citibikes for male and female customers.
