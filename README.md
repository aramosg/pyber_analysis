# Module 5 – PyBer with Matplotlib
# Unit Challenge

## Overview of the Project
After analyzing the ride data and so some interesting discoveries, we have been assigned with a new task: We need to analyze the provided data and compare the total weekly fares per type of city (Rural, Urban, and Suburban). After doing it, we need to provide recommendations to the Leadership Team about how to improve the company's situation. 

## Results of the analysis
The following image describes the summary data frame, which is the foundation for our analysis:

![PyBer Summary DataFrame](/analysis/summary_df.png)

By looking at this data frame, we can see some interesting facts:
1. The rural area has the highest average fare per driver
2. The rural area has the highest average fare per ride
3. The urban area has the highest fares with $39,854.38
4. The urban area is the one with more drivers: 2,405 drivers
5. The urban area is where most of the rides happen: 1,625 rides

![PyBer - Total fare by city typess](/analysis/PyBer_fare_summary.png)

Now, comparing the total fare by city types, two events are grabbing my attention:
1. Fares for all city types had a peak by the end of February. Why? What happened? Did the company do anything different during that period of time to cause that upward trend? Any special events?
2. The Suburban Cities have experience a similar peak by the end of April. Urban and rural cities do not experience a peak again after reaching their hights level in February - March.

Other than the previous highlights, fares remain very much stable throught the analyzed period of time. Of course, it is worth mentioning than despite having much less drivers, rural cities have the best performing indicators.

It is interesting to think what would happen if we would the variables of average distance traveled and average duration of trip. By adding these metrics, I think it would be possible to determine the requirements of any city type. Urban areas may be have excess drivers, while rural areas may need some new drivers.

Adding to the above point, let us just analyze the average total rides per driver:
- Rural: 125 rides, 78 drivers > 1.6 rides per driver
- Suburban: 625 rides, 490 drivers > 1.27 rides per driver
- Urban: 1,625 rides, 2,405 drivers > 0.67 rides per driver

What does it mean? If you ask me, there are too many drivers in the urban areas. And since the offer is higher than the demand, this is why we may have a lower fare average for the urban areas. This is a hypothesis worth exploring.

## Summary
After summarizing the findings of our analysis, these are my recommmendations
1. Explore the possibility of adding average distance per ride and average duration of ride - This may reveal how busy or idle are our drivers.
2. Exploring the possibility of adding new services, such as delivery - For instance, urban areas may have an excess of drivers. Why not assigning these drivers to other tasks, such as the delivery/courier services. Also, a high value service where we can charge a higher fare may be useful (limousines, luxury cars, and customized service)
3. Increase the number of drivers in rural areas - We can increase the availability of drivers in rural areas. Of course, doing a deeper analysis about how busy te drivers are is paramount for this effort. 
4. Identify events triggering an upwards trend in fares - As mentioned earlier, we need to identifi the events that are causing our average fares to go up. Although apparently the effect is temporary, if identified, we may be able to keep that effect longer. 
5. Customer satisfaction surveys - How are our drivers doing when it comes to customer service? We can see in our graph a downwards trend during some periods of time. It can be very useful for us if this negative trends can be reverted or they are totally out of control (market events we cannot stop or modify)

## Conclusion?

###### ---------------------------------------------------------