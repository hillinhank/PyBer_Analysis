# PyBer_Analysis
# Overview
The purpose of the new analysis was to visualize the ride sharing data. Using our new skills in both matplotlib and pandas, we gathered the data from the raw csv files, and created a summary dataframe. Then, using a combination of several functions including groupby(), sum(), pivot(), resample(), and df.plot(), we created a multiple line plot that shows the total weekly fares for each type of city.
# Results
## Deliverable 1
![image](https://user-images.githubusercontent.com/101481759/164747516-e20c0de9-e266-4209-bf0c-b91e0f44d037.png)

As we can see, due to population density Total Rides, Total Drivers, and Total Fares were all substantially increased in Urban areas. Conversely, the Average Fare Per Ride and Average Fare Per Driver were increased the greatest in Rural areas, likely due to distance. 
## Deliverable 2
![image](https://user-images.githubusercontent.com/101481759/164747539-7cf40664-f254-48a5-abcf-80f0ac3f6168.png)

The most interesting aspect of this chart is the sudden drop in rides in the month of April. This displays the inverse relationship between the Urban, Suburban, and Rural  areas, respectively. There is a major drop in Urban areas in April, a moderate drop in Suburban areas, and Rural areas remains unaffected. This drop, or lack thereof, likely has a direct relationship to the “walkability” of the area. Urban areas are the most walkable, and with weather improving it seems less people are choosing to ride with Pyber.
# Summary
Several suggestions I would like make:
-Considering over two-thirds of all rides come from Urban areas, it may be beneficial to offer customer incentives in months with nice weather. Volume and customer loyalty are key.
- In both Rural and Suburban areas, Pybers Average Fare Per Ride is less than their Average Fare Per Driver. Pyber is taking a financial loss in these areas, it may be necessary to simply charge more per ride in Rural areas, or to not offer their services in certain areas.
- Lastly, there are more Total Drivers in Urban areas than there are Total Rides. Steps need to be taken to increase the total rides in this area. 
