# PyBer_Analysis
Module 5: PyBer with Matplotlib
# Module 5 Challenge

## Overview
We have been working with Omar on working visualizing ride share data by creating all different types of charts. We are now going to create a summary data frame of the data by city type. Then we will create a multiple-line graph that shows the total weekly fare for each city type. We will then analyze our new data frame and line graph. 

## Results
The data frame that contains the summary of the results holds data from January through the first 2 weeks of May, where the line chart only displays the data from January 1 – April 29. 
### Summary of Results – By City Type 
<img width="596" alt="PyBer_Sum_df" src="https://user-images.githubusercontent.com/79118630/113033720-517d0300-915f-11eb-8fac-b1f380735ca1.png">

- Total rides and total drivers share similar patterns as rural having the least amount, suburban second and urban with the most. This is not a shock as urban populations are typically more densely populated and tend to host more office/work space locations. Since not everybody drives, owns a car, or even urban traffic may to be bad so it’s not worth the gas money, it makes sense that there are more rides in urban areas. One thing that is different is that there are more urban drivers than urban rides. Compared to suburban and rural areas where their driver counts are lower than the ride count. This can be explained by looking at worker supply and demand. As a driver, in order to make money, you need to drive people, so it would make sense that more drivers would flock towards the urban areas.
- Average fare per ride is highest with rural, suburban second and urban last. Even though urban compared to rural has nine times more total fares, urban has over ten times the total rides, this is why rural drivers are earning an average of $10 more per ride. 
- Average fare per driver, similar to fare per ride, rural has the highest, suburban second and urban with the lowest. Rural stands pretty high on the leaderboard for this category. On average, rural fares per driver are $15 more than suburban and $45 more than urban drivers. One thing that should be noted should be since the urban total driver count is greater than the urban total ride count, the urban fare per driver will be an is lower than the urban fare per ride. 
- Going back to that idea of worker supply and demand, someone who hasn’t looked at this would think it would be a good idea to spend more time in urban areas because there are more chances to work. However, if we showed that driver this summary, he might think otherwise. There is in-fact a worker surplus in the urban areas, there are more drivers than rides, an average wage a driver will make is lower than the average fare is charged. 

### Line Chart
![fig8](https://user-images.githubusercontent.com/79118630/113033750-5b066b00-915f-11eb-85ac-85547e9ba13b.png)

- This multiple line chart just displays the total fares by city type, where each dip or peak is the total fare for the week. This helps with looking at trends. The biggest standout is the giant dip that urban takes at the beginning of April, and suburban dips as well. One reason for this there could have been an error or typos in the data set, or there was a true dip in fares during this time. 
## Summary 
### Business recommendations
#### Limit Urban Drivers
- There was a tremendous surplus of drivers than rides in the urban areas. Limiting or even warning the driver that there are many active drivers in the current urban area would encourage the driver to venture outside to potentially get more rides. Urban drivers were earning fares less than the urban average fare. If a driver knows this, they will not want to drive in urban areas and will want to go suburban and potentially rural areas. This will help the company because drivers are now becoming more available in other areas, people will then to think of them when they need to be driven somewhere. 
#### Track Driver data
- Tracking driver data location can also help explain this data. This can help see how many of these drivers do both urban and suburban areas, and potentially rural. In a lot of urban areas where it is filled with work offices, a lot of people who have families and live in suburban areas will work in urban areas. So is it an urban ride if it starts in the suburb, is it urban? What about going from urban to suburban? Tracking this and defining it, or even making a new row or new data frame will be helpful.
#### Instead of weekly; use weekday and weekend charts
- This will help with promotions by seeing how fares different by the day. Is the company making more money during the week by people trying to get to and from work, or are they making more money from people visiting friends or going out on the weekends? Looking at city type for this kind of analysis will still be helpful but not necessary. This would look at and better gauge when to promote drivers to be active and what deals/incentives to provide to riders and when. 
