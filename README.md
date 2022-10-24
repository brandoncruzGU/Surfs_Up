# Surfs Up Challenge

## Overview

W.Avy wants to further the analysis of the temperatures in Oahu before opening his surf and ice cream shop. He wants us to gather all of the temperature data from June and December to determine whether or not the surf and ice cream shop will be sustainable all year long. I was able to quickly extract this data using a SQL Alchemy query that filtered the data to show all of the temperatures from June and December. I then converted the data into a data frame that produced the summary statistics by using the describe function.

## Results

### June Summary Statistics
![image](https://user-images.githubusercontent.com/107777321/197466445-36f14333-2a4a-4f66-a491-7a937612b44b.png)


### December Summary Statistics
![image](https://user-images.githubusercontent.com/107777321/197466600-a647f9c6-bbff-43f3-a4b9-f685698ddbcd.png)

### Key Takeaways
The average temperatures in both months are fairly similar. The average temperature in June is 75 degrees and the average temperature in December is 71 degrees. There is only a 4 degree difference in the two averages which isn't too much of a concern.

The minimum temperatures in June and December are 64 degrees and 56 degrees respectively. These minimums are likely outliers and fall outside of the inter-quartile range. Although the difference between the two minimum temperatures are much greater than the difference btween the average temperatures, it is unlikely that the temperature will consistently fall below 60 degrees.

The maximum temperatures in June and December have a difference of two degrees. The maximum temperature in June is 85 degrees and the maximum temperature in December is 83 degrees. These temperatures provide an ideal climate for customers to enjoy ice cream and surfing.

## Summary
Our analysis shows that there is little to no difference between the temperature in June and December. Although there are days when the temperature may fall outside of the usual 70 degree range, this should not have a significant impact on the ice cream surf shop. All together, the weather in these two months provides an ideal climate where customers can enjoy ice cream and surfing. 

To deepen our findings, we could run an analysis on the two months to compare the descriptive statistics of the precipitation levels and wind speeds in Oahu. Since the island temperature is consistent for most of the year, the amount of rain and the wind speeds are more likely to have a greater impact on the sustainability of the business. If wind speeds are higher in a certain month, then we might predict that the waters are more dangerous for people to surf. If the levels of precipitation are higher in a certain month, then customers may feel less inclined to visit the shop. These two metrics may be able to provide W.Avy with better insights to have a sustainable and successful business.
