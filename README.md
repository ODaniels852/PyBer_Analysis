# An Analysis of Rideshare Data

## Project Overview
As a new data analyst at PyBer, a ride-sharing app, I was tasked with analyzing all the rideshare data from January to early May of 2019. This analysis consisted of a review of driver, fare and city information for rides in three city types: urban, suburban, and rural. In addition to my analysis, I created a visualization of my findings to be presented to the company CEO. Some of this initial analysis involved the summarization of the percentage of fares by city type, percentage of drivers for each city type and average number of drivers for each city type.

After completing my initial analysis, I was given a new assignment requiring the creation of a summary DataFrame of the ride-sharing data, as well as a multiple-line graph that shows the total weekly fares for each city type. The goal of this additional analysis is to identify differences by city type, information that is beneficial for the decision-makers at PyBer.

### Results

**Rides, Drivers, Fares and Average fares by City Type**
Review of analysis results show that urban areas utilize the PyBer rideshare program the most of the three city types. Of the approximately $65k of fares, about $40k was earned in urban areas. Rural areas utilize the PyBer rideshare service the least, with only 125 rides in the period under review, while total rides during this period totaled 2,375. However, there is a clear inverse relationship between the utilization of this service in rural and urban areas, and the average fare per driver. The average fare in rural areas was about $55, and only about $17 in urban areas. Overall, performance in the Suburban area stands out because, although total fares earned in this area was about $19k, or about half of the total fares earned in urban areas, it only took 625 rides, or a little over a third of the number of rides in urban areas to accomplish this.

<sub>These results can be viewed in further detail in the DataFrame below.</sub>
<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/PyBer_Analysis/raw/main/Resources/pyber_summary_df.png">
<img alt=" Shows the ride, driver, fare, and average far summaries by city type."/>

</picture> 

**Analysis of Weekly Fares by City Type**
When analysis was tracked weekly and visualized on a line graph the tiered performance of the 3 city types is very easily visible. Most fares were earned in urban areas, followed by suburban areas, and lastly rural areas. Both urban and suburban fares were lowest in the first week of January, while fares earned in rural areas hit lows both in January and mid-February. Urban fares stayed above $2k each week, except for the weeks of January 6th and January 20th. All city types experienced a spike in the final week of February. Suburban areas experienced a very large drop in fares during beginning of March, the most notable decline from one week to the next of any of the city types.

<sub>These results can be viewed in further detail in the line chart below.</sub>
<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/PyBer_Analysis/raw/main/analysis/PyBer_fare_summary.png">
<img alt=" Shows the ride, driver, fare, and average far summaries by city type."/>

</picture> 

##  Summary
In summary, I would like to make the following recommendations to the PyBer CEO based on my analysis and findings:
1)	Increase presence in suburban areas as the company generates higher average fares than in urban areas
2)	Increase presence in rural areas, but not too drastically, the demand doesn’t seem to be as high
3)	The urban market seems to be a bit saturated, if possible drivers should be redirected to suburban areas 
