# Citibike Bikesharing Usage Visualizations 

## Overview
I've decided to launch a bikesharing company in Des Moines, IA. After having such a pleseant experience in New York City using the bike share system Citi Bike, I decided to create some visualizations from available Citi Bike Data to better understand how they work.


Link to the tableau story: 

[Citibike Usage Visualizations](https://prod-useast-b.online.tableau.com/t/larrywatsonstableausite/views/CitibikeUsageVisualizations/CitibikeUsageVisualizations/watson.lawrence.e@gmail.com/6394a883-eb3b-46d9-bd6a-01233dace095?:display_count=n&:showVizHome=n&:origin=viz_share_link)

### Results

![start](https://github.com/watsonlarry/bikesharing/blob/main/Resources/start.png)

![stop](https://github.com/watsonlarry/bikesharing/blob/main/Resources/stop.png)

First, we want to establish the primary geographicaal area of use. Citi Bike bikes can be found through out all the burroughs in central NYC but with theses maps we can seee that a majority of the trips are stated and ended in south Manhattan. 

![viz1](https://github.com/watsonlarry/bikesharing/blob/main/Resources/viz1.png)

![viz2](https://github.com/watsonlarry/bikesharing/blob/main/Resources/viz2.png)

With these generated graphs we can pull info about two valuable sections of data: users ride duration and usage by gender.  Both graphs tell the same story about average ride duration. Looking at bike checkout times for 24-hour pass NYC users, we see that most riders are using their bikes for about 5-6 hours. Also, notice the sharp incline from 1-5 hour duration and the very gradual decline from 5-24 hour duration. The second graph plots the same information but makes a distiction between male, female, and unknown gender usage. The graphs for men and women largely follow the same usage path, though there is a key distiction: there are about 3x more men using the service. The unknown gender does not register much information on the graph.

![viz3](https://github.com/watsonlarry/bikesharing/blob/main/Resources/viz3.png)

The heat map successfully vizualizes the most popular times of day for bike rentals throughout the week. The hot times follow two different patterns, one for the weekdays and one for the weekends. During the weekdays 6-9am and 5-7pm are popular, suggesting a pre/post 9-5 work usage. On the weekends is concentrated in the middle of the day from 10am-7pm.

![viz4](https://github.com/watsonlarry/bikesharing/blob/main/Resources/viz4.png)

With this visualization we see the previously identified gender-based observations repeated. While there are a greater number of males using the service the weekday/weekend usage trends are the same regardless of gender. 

![viz5](https://github.com/watsonlarry/bikesharing/blob/main/Resources/viz5.png)

In this last vizualization we see a pretty clear picture that annual subscription users are riding more often than daily subscribers throughout week.

## Conclusion

1. An area to explore is the number of tourists using the service in NYC. It's important to note the impact of tourism on the service since the idea is to transplant a similar business to Des Moines, IA--a smaller city with far fewer tourists. We've already identified the annual pass riders are riding more often than daily pass users, and it's probably safe to assume annual users are NYC residents, but we can't make that distinction for daily pass riders. We should also pull hourly riders into the vizualization to get a clearer picture of all the riders.

2. I would also love to find a way to visualize the average trip length. In terms of square footage, Manhattan is significantly smaller than Des Moines (22.82 mi² 90.66 mi² (though, this is the whole Des Moines metro-area, couldn't find stats on downtown's area)) and much more dense. It's possible that people in NYC are making much shorter trips than would be possible in Des Moines. 
