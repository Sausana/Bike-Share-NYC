### NYC Bike Share Analysis
NYC Bike Share:

Link to dashboard:https://public.tableau.com/views/BikeShareChallenge_16738372165510/BikeShareChallenge?:language=en-US&:display_count=n&:origin=viz_share_link

# Overview:
The purpose of this project is to use Tableau Public and Pandas and a set of bikeshare data from 2019 in New York City to convince investors that a bike-sharing program in Des Moines is a good business proposal. In this analysis, we use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we created a set of visualizations to:
Show the length of time that bikes are checked out for all riders and genders Show the number of bike trips for all riders and genders for each hour of each day of the week Show the number of bike trips for each type of user and gender for each day of the week.

### Results
For the first part of this project, we needed to use Pandas in order to have 'Tripduration' in the correct Datetime format
![image_name](Images/TripDuration.png)


## Gender Breakdown
The third item I think is important for this data analysis to show the breakdown of gender since a significant factor in our later analysis includes gender breakdowns. In this Gender Breakdown Analysis, Men make up the majority of riders at roughly 65% of all riders.

![image_name](Images/Gender_Breakdown.png)

# August Peak Hours
The second item on my story is taken from the module work with the August Peak Hours. I think it is important for investors to see the higher usage hours because it can indicate whether it would be likely that users will use it to commute. Some of the peak hours in this analysis are from 8-9a.m. and 4-7p.m.. These are likely due to travelers (and mostly subscribers) going to and from work to reduce times in high traffic areas.

![image_name](Images/Peak_time_for_users.png)



## Checkout Time for Users
Checkout Time for Users shows the amount of time that a user spends on a bike. You can see from this line graph that riders tend to use the bike share for less than an hour. The majority of users will utilize a citibike for 20 minutes or less.

![image_name](Images/Checkout_time_for_users)


## Checkout Times by Gender
Checkout Times by Gender continues to show further analysis on the previous graph, depicting a similiar trend of ride times by all genders. However, men do tend to ride for slightly longer periods of time than women.

![image_name](Images/Checkout_time_for_genders)


## Trips by Weekday per Hour
In this heatmap, we are able to visually depict that weekdays during peak commute times (7-9a.m. & 5-7p/m/) have higher user counts than throughout the day. On the contrary, weekends tend to have higher user counts during the hours of 10a.m. and 6p.m. which could be a result of tourism and the times that tourist attractions are open during the weekends and/or when residents conduct errands.

![image_name](Images/Trips_by_weekday_per_hour)


## Trips be Gender (Weekday per Hour)
Trips by Gender heatmap follows a similar pattern as the Trips by Weekday heatmap for both gender, however, as previously mentioned, males utilize the bikeshare far more frequently than females.

![image_name](Images/Trips_be_Gender (Weekday per Hour))

## User Trips by Gender by Weekday
The User Trips by Gender by Weekday shows the difference in number of riders based on whether a user is a subscriber and uses the bikeshare regularly versus a customer who uses it just once in a while or may be a tourist. As shown in pervious heatmaps and time charts, male subscribers are the majority of users of the bikeshare business, and the more utilized days are during the work week indicating that the bikeshare is likely a form of transportation for commuting to work.

![image_name](Images/Trips_be_Gender (Weekday per Hour))

## User Trips by Gender by Weekday
The User Trips by Gender by Weekday shows the difference in number of riders based on whether a user is a subscriber and uses the bikeshare regularly versus a customer who uses it just once in a while or may be a tourist. As shown in pervious heatmaps and time charts, male subscribers are the majority of users of the bikeshare business, and the more utilized days are during the work week indicating that the bikeshare is likely a form of transportation for commuting to work.

![image_name](Images/User_trips_by_Gender(by weekday))


## Summary
The NYC CitiBike Analysis provides a well-rounded exposure to many aspects that will help develop a Bike-Share program. The data above depicts the type of users, the majority of users by gender, as well as the hours of the day during each day of the week that the bikes are utilitzed. The analysis I would recommend doing would require a different dataset and would be more comparative to New York City and Des Moines, IA. While the NYC CitiBike Data helps to paint the picture of who will be using it the most and when they will be using it, it does not depict the differences in NYC and Des Moines. An addiitonal analyis I would recommend is distances traveled. The distance traveled could help with the breakdown of how many miles a bike travels and how often the bikes need to be in maintenance, as briefly mentioned in the module, and how much it would cost in order to order to maintain the bikes. Some other questions I would have before starting this bike-share business is does Des Moines have the population and traffic density that NYC has that encourages people to use a bikeshare? How much does each bike share cost and do they anticipate the number of rides to be similiar and will that outweigh the costs the purchase all of the bikes and conduct their maintenance? The last question I would have is in many major cities there are more than one bike-share business for customers to choose from. What makes this bike-share more attractive that a user would want to use this one instead of another?
