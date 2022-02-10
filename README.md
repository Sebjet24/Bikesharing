# Bikesharing

## Overview of the Statistical Analysis

### Purpose:

There is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. For this analysis, I'll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
 - Show the length of time that bikes are checked out for all riders and genders
 - Show the number of bike trips for all riders and genders for each hour of each day of the week
 - Show the number of bike trips for each type of user and gender for each day of the week
Finally, I’ll add these new visualizations to the two I created in this module for my final presentation and analysis to pitch to investors.

## Results:
Link to Tableau:
[Sebastian's NYC Citibike Analysis](https://public.tableau.com/app/profile/sebastian.scholl/viz/NYC_CitiBike_Challenge_Trip_Analysis_16444545557670/NYCCitibikeStory?publish=yes "Sebastian's NYC Citibike Analysis")

### Top Starting Locations

![Top_Starting_Locations](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Top_Starting_Locations.PNG)

In New York City, the most common sites for Citibike clients to start their travels are:
1. Pershing Square
2. Broadway
3. Tribecca Bridge

### Top Ending Locations

![Top_Ending_Locations](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Top_Ending_Locations.PNG)

 - In New York City, the most popular places for Citibike customers to end their journeys are the same places where they started.

### Checkout Times for Users

![Checkout_Times_for_Users](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Checkout_Times_for_Users.PNG)

 - The peak usage time for NYC Citibikes is 5 minutes. In August 2019, 146,752 bikes were checked out in 5 minutes. For at least 2 hours and 59 minutes, 33 Citibikes were checked out.

### Checkout Times by Gender

![Checkout_Times_by_Gender](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Checkout_Times_by_Gender.PNG)

 - In August 2019, males were the most frequent users of Citibikes. At peak usage, there were 34,151 female Citibike users, which is 68.4 percent less than male riders.

### Trips by Weekday

![Trips_by_Weekday](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Trips_by_Weekday.PNG)

 - Between the hours of 12 a.m. and 5 a.m. on Sundays through Saturdays, Citibikes are utilized the least.

### Trips by Gender (Weekday per Hour)

![Trips_by_Gender_(Weekday_per_Hour)](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/Trips_by_Gender_(Weekday_per_Hour).PNG)

 - Men and women ride Citibikes at 8 a.m., 5 p.m., and 6 p.m. Monday through Friday. Saturdays between 9 a.m. and 7 p.m. are popular for both male and female bikers. Between 11 a.m. and 5 p.m. on Sundays, male and female riders tend to utilize Citibikes the most.

### User Trips by Gender by Weekday

![User_Trips_by_Gender_by_Weekday](https://github.com/Sebjet24/Bikesharing/blob/main/Resources/User_Trips_by_Gender_by_Weekday.PNG)

 - Thursdays are the most popular days to utilize Citibikes among male and female subscribers. For both male and female clients, Sundays were the most popular days to utilize Citibikes.

## Summary:
In August 2019, males were the predominant users of Citibikes in New York City. On Thursdays, the most rides were taken, and the starting and finishing points of Citibike excursions were the same. More research is required to establish whether Citibikes is a good match for Des Moines, Iowa.

Analysts should map population growth between Des Moines and New York City to see if Citibikes is a suitable fit for Des Moines, Iowa. The two cities' population totals and growth rates might be compared using publicly accessible census data. If Des Moines' population grows faster than New York City's, the Citibikes system may be a fantastic fit for the city.

Correlating weather data between Des Moines and New York City is another visualization that may aid investors in determining if Citibikes are a good fit for Des Moines. If the temperatures and weather are similar, it will be easier for investors to see why Citibikes is a good fit for Des Moines, Iowa.
