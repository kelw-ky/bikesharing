# bikesharing

## Overview:
Creating a story using Tableau and 2019 data to display the bike-sharing program in Des Moiines. 

For this analysis, we will be using Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week. 

Please [CLICK HERE](https://public.tableau.com/app/profile/kelly5613/viz/NYCCitibike_16495643629280/NYCCitibike-KeyAnalysis) to see the NYC Citibike Tableau Story. 

## Results:

1. Top Starting Locations: This map shows the top starting locations the users for the bike-sharing program prefers. The darker the shade and the larger the circles shows the more amount of users are preferring to start at these locations.

![Top_Starting_Location](/Resources/Images/Top_Starting_Location.png)

2. Top Ending Locations: This map shows the top end locations the users for the bike-sharing program prefers. Similar to the map mentioned above the darker the shade and the larger the circles shows the more amount of users are preferring to end at these locations. 

![Top_Ending_Location](/Resources/Images/Top_Ending_Location.png)

3. Checkout Times by User: In this line graph, it shows that there are close to no riders past the one hour mark. The line peaked at the 5 minute mark and there was the most rides between 1 to 25 minutes. 

![Checkout_Times_for_Users](/Resources/Images/Checkout_Times_for_Users.png)

4. Checkout Times by Gender: The line graph had the same trend as the graph above, where the peak amount of riders is at the 5 and 6 minute mark. There are significantly more male riders than females or unknown riders. 

![Checkout_Times_by_Gender](/Resources/Images/Checkout_Times_by_Gender.png)

5. Trips by Weekday: In this heat map, it clearly shows that there was the most riders on Mondays, Tuesdays, and Thursdays at 5pm and 6 pm. The darker the map the more amount of riders there are. 

![Trips_by_Weekday_per_Hour](/Resources/Images/Trips_by_Weekday_per_Hour.png)

6. Trips by Gender: The trend mentioned in the map above can be more easily seen on the male heat map as there were more male riders. In the female heatmap, although it is not as clear in colour, it shows the trend of the most riders during Mondays, Tuesdays, and Thursdays at 5pm and 6 pm. 

![Trips_by_Gender](/Resources/Images/Trips_by_Gender.png)

7. User Trips by Gender: From this heat map, we can see that there are annual subscriber with identified gender. Following the similar trend, there are the most trips made on Mondays, Tuesdays, Thursdays and Fridays for males and the most females on Mondays, Tuesdays and Thurdays

![User_Trips_Gender](/Resources/Images/User_Trips_Gender.png)


## Summary:

From the NYC Citibike - Key Analysis story on Tableau, most riders like to start and end their trip in the same locations as we look at the Top Starting Location and Top Ending Location maps. The most common checkout times peaks at 5 minutes and most popular checkout time ranges between 1 to 25 minutes. The bike-sharing program is most used on Mondays, Tuesdays, Thursdays and Fridays on 5pm and 6pm. 
