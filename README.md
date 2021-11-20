# Bikesharing with NYC Citibike data

This is an analysis of NYC CitiBike bikesharing data from August 2019, with Tableau.

## Overview

This Tableau storcy can be seen here: [Bikesharing Tableau Story](https://public.tableau.com/views/NYCCitiBikeStory_16374220173300/BikeSharingAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

The framework for this project was based on bikeshare data from CitiBike in New York City for presentation to investors looking to begin a bikesharing program in Des Moines, Ioaw. While Des Moines is a long way away from NYC, this analysis might help answer a few key questions:

-How much are the bikes used and by whow?
-What is the percentage of users based on gender?
-What time of day are bikes used the most and the least?
-What area of a city sees the most bikeshare usage?

## Results

While the demographics of an inner city like Des Moines may be different from those that live in NYC, a review of CitiBike riders may shine light on who bikeshare might appeal to, regardles of locale.

![Usertype and Subscribers](https://user-images.githubusercontent.com/88256967/142732498-305c30f1-e43a-41b3-a65a-19d7db0446e0.PNG)

![Customer Ride Count](https://user-images.githubusercontent.com/88256967/142732500-b0525afa-0c88-4447-82b9-8cd20cefc97e.PNG)
![Customer by Gender](https://user-images.githubusercontent.com/88256967/142732571-7e87716e-6405-4385-a98e-e738b9775354.PNG)

In the above images we can see that greater than 3/4 of the users are Subscribers, who make regular use of the bike and are a predictable source of income for the program. Bikeshare program users are also predominatly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.

-----------------------------------------------------------------------------------------

![Top Starting Locations](https://user-images.githubusercontent.com/88256967/142732645-0a4d31ba-5551-43ac-920d-24e5c3abefad.PNG)

The above map displays the top bikesharing start locations. The size of the circles and darkness of the blue indicates the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the Lower Manhattan, known for tall office buildings, densely packed residential skyscrapers, and entertainment venues. Bike usage is lower in the less densely packed surrounding neighborhoods.

-----------------------------------
![August Peak Hours of Usage](https://user-images.githubusercontent.com/88256967/142732761-7190991c-c01b-4972-b2fe-17e8a526e2ab.PNG)

This chart above displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August 2019. We can see the lowest usage hours between 2 AM and 5 AM, which becomes the best time to conduct bike repairs and redistribution of bikes from full stations to less-full stations.

--------------------------------------------------------------------------------------------------
![Trips by Weekday per Hour](https://user-images.githubusercontent.com/88256967/142732842-ff7673f7-c315-4223-a5a7-bea631f24700.PNG)

The heatmap above helps show weekly usage patterns. An interesting anomaly that can be identified here is the relatively low bike usage during Wednesday's end of day commute. Also this heatmap further confirms the low usage of early morning as we concluded prior.

---------------------------------------------------------
![Average Trip Duration](https://user-images.githubusercontent.com/88256967/142732978-a714a062-2654-450a-b8bb-87a941fc1de9.PNG)

The chart above shows the average trip duration by birth year. The bikesharing userbase covers all age demographics as you can see from usage of birth year. Also take note that teenagers and young adults in their early twenties enjoy taking much longer bikerides than older users.

----------------------------------------------------------------
![Heatmap Gender Weekday](https://user-images.githubusercontent.com/88256967/142733080-60b6a47e-6d68-4088-b991-bb13004210da.PNG)

Lastly, the heatmap above reinforces how much the userbase is dominated by male identifying subscribing users. 

## Summary

In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. THe user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem to be the most reliable market. Main usage seems focused around morning and evening commute times.

If I were to further research additional inquiry for analysis and visualization, given the data provided, I would explore:
- Trip Duration time for subscribers vs. non-subscribers
- Amount of non-subscribers the are returning non-subscribers
- Difference in male and female during the hours of usage on weekdays vs. weekend.




