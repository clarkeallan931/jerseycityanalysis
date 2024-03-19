Clarke Allan
UT Boot Camp
Jersey City Citi Bike Analysis



Goal of Analyis: Look to better publicize and imporve Jersey City's Citi Bike program.

How did I do this? Created dashboards that analyzed............
    1. Most Frequently Used Start and End Stations by Month and Year.
    2. Rides start and end by station, month, and day of the week.
    3. Start and End Stations with the most rides. 
    4. Most frequent start stations by end point and most end stations by starting point. 
    5. Times of the day with the most rides. 
    6. Day of the week with the most rides (by start station and end station).
    7. Starting and ending stations with the longest trip distance. 
    8. Starting and ending stations with the longest trip duration.
    9. Most efficient stations (Distance/Duration)


1.Most Frequently Used Start and End Stations by Month and Year.

Insights: Goal of the maps was to see where people were starting and ending their rides most frequently. This could give businesses and the city a better understanding of where people want to be. Where do you build an office? Where do you advertise? We can also analyze how these spots change by month and year. There is a better graph for that later in the story. Overally it looks like most people start for Grove Street and head north east. Most of the end stations are near the water which makes sense since people like to spend their time near water. 

You can also use this map to see what parts of the city need to be imporved. I looks like more can be added farther away from the coast to draw people to those locations. 

2.Rides start and end by station, month, and day of the week.

As stated earlier, this graph gives a much better monthy breakdown of where people start and end rides. You have the ability to look at one station or multiple stations at once. I also added day of the week for further analysis. Grove Street is a good representation of the population as a whole since it is the biggest hub. It looks like overally traffic peaks during the summer and declines toward the winter. The city could use this to determine how many stations they keep open during the winter months to cut costs and improve margins. 

3.Start and End Stations with the most rides. 

You could get this information on the map, but I wanted to show it in a different format so the reader can better understand the money stations. This is great for busiesses looking to find office space or advertise. The city could also consider building more stations near these areas if there are efficiency issues. 


4.Most frequent start stations by end point and most end stations by starting point. 

This could help give the user an understanding of where people are looking to bike. What makes these areas desirable? Should we have more end/start stations? Could help understand supply and demand. 

5.Times of the day with the most rides. 

When do people ride? 

Predictably the top end times are 7 AM and 8 PM (Grove) showing that people work and ride to Grove St. Top start times are after work (5 - 6 PM). This is good information to help the city come up with non-work use cases and better leverage events outside of work. Also the number gets low at night (safety). The city could consider safety precautions to help get people riding at odd times (less likely).



6.Rides by Day of Week

Similar to story 2, but this gives you an overall total and a different style graph (single bar vs double bar). 

7.Starting and ending stations with the longest trip distance. 

Similar to most rides, wanted to get an understanding of total use in terms of miles traveled vs. rides to see if results differed. My distance calcualtion as (start long - start lat), (end long - end lat). I used the Haversine formula (ChatGPT) and the multipled by .621371 to convert to miles. 

8.Starting and ending stations with the longest trip duration.

Where are riders spending time? This is another measure of use that can determine where to build/relocate stations. I calculated duration by subtracting ended_at and started_at. One can also look at this dashboard and understand why South Waterfront has the most time. It was interesting the Grove had more distance and less durantion? Is there an efficiency issue? Next story

9.Most efficient stations (Distance/Duration)

Wanted to understand where there was more traffic (less efficiency) and smoother rides (more efficiency). My efficiency calcualtion was distance (miles)/ duration (started_at - ended_at). Although I had good intent, I think there are some issues with the day. Broadway and W 36th has a duration of .00003 skewing the first graph. On the bottom right graph W 34th also has duration of .48. 

The end goal of this graph was to see if the city could make paths to improve efficiency. In order to do that, they need to see where rides are less efficient. I do not think these graphs are usable beacause of bad data. 








