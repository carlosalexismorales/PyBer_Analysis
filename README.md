# Pyber Analysis

Using Python, Pandas, and Jupyter Lab to create a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type. Additionally, submitting a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Project Overview

The purpose of this project is to perform exploratory data analysis of Pyber's ride sharing data in order to help Pyber's decision makers address accessibility and affordability on areas with key metrics. This is done by creating visualizations of the metrics of the data, such as, ridership and fare metrics by the types of cities in which Pyber operates, with line graphs and data frames, respectively. Creating visualizations of this data can help illustrate which city/area types needs improvement or change to help improve Pyber's ride-sharing services.


## Challenge Overview


- Import your data into a Pandas DataFrame.
- Merge your DataFrames.
- Determine the mean, median, and mode for the following:
 - The total number of rides for each city type
 - The average fares for each city type.
 - The total number of drivers for each citv type.



## Resources

- Data Source:
  - city_data.csv
  - ride_data.csv
 
 - Software:
   - Python 3.10.5
   - Conda 4.13.0
   - Jupyter Notebook 6.4.11
   - Pandas 1.4.2

## Results 

As shown in the DataFrame image below, it appears that riders in urban areas pay on average almost $10 less for PyBer than riders in rural areas. The average fare per ride is approximately $25 in urban areas, compared to the average fare per ride of $35 in rural areas. The average fare per ride for suburban areas lands between the previous two at around $31. While this is an indication that rides in rural areas are more costly than elsewhere, we would need more data to interpret as to why this may occur. One piece of data that does give some context to this obversation is the average fare per driver. In rural areas, we see that this particular area has the highest average of fare per driver at around $55. In suburban areas, it is around $40 and in urban, it is about $17. This indicates that consumers are paying more for drivers in rural areas than anywhere else. This could be because of the amount of riders that are in each of these areas. To clarify, we see that the image below illustrates that there are only 78 drivers in rural areas compared to the 2,405 drivers in urban areas. Given that there is a greater usage of PyBer in urban areas, the total fares are consequently also higher than suburban and rural areas. PyBer transactions in urban areas totaled nearly $40,000 whereas transactions in urban areas and rural areas totaled at least $19,000 and $4,000, respectively. This is a major difference that can provide context as to why there aren't as many rides or drivers in rural areas. Again, this can be due to the density of the population and destination locations in those areas, with locations usually being farther in rural/countryside areas than urban or suburban ones, but we would need more data to have a deeper understanding of this. 



<img width="593" alt="Screen Shot 2022-06-29 at 4 14 56 PM" src="https://user-images.githubusercontent.com/102444078/176561161-9b5f4a8f-dcd1-43fd-aa40-c1c674e1df61.png">




As shown in the multiple-line graph image below, we can see trends of total fares in rural, suburban, and urban cities between January 2019 and April 2019. This supports the PyBer Summary DataFrame because it shows how the urban areas had the highest total fare, ranging around $1,600 to $2,300, within the months of January to April 2019. We also see that this was followed by the second-highest total fare, which were urban areas, that had fares ranging from about $750 to $1,400, in the same amount of time. The lowest total was represented by the rural areas: theirs hovered around $300 all throughout the same time period. These low fares can be attributed to the empty cells observed in the rural cities column after arranging the data into the specified date range using the loc function. Ultimately, the drop in the number of ride usage in the rural cities within the months of January to April, 2019 could be due to the low number of available rides and drivers, therefore, by providing more resources, such as more affordable and cheaper rides and an abundant amount of drivers, this can subsequently bring in more revenue while also making it more accessible to more consumers.



<img width="906" alt="Screen Shot 2022-06-29 at 8 47 32 PM" src="https://user-images.githubusercontent.com/102444078/176588540-b533d561-2287-4022-b73f-56e374a93be0.png">



## Summary

Now that we have a better understanding of the ride-sharing data, we can summarize three business recommendations to address the disparities among the city types.

1. We can take a look at more data: specficially the demographic and geographic data pertaining to each of the city types. We can specify which information we want to analyze, such as the population and age range within the demographic data and the average travel distance and popular landmarks within the geographic data. For example, we can group the rides by age and city and see which type of riders average more rides than other groups. This information can be analyzed and provide a better picture as to any disparity.
2. We can analyze previous data: specifically looking back at other years than 2019. The data was that analyzed in this assignment only look at a select number of months - from January to April. This can bring false pretenses because we're only looking at a specific time, however, with data from previous months or years, we can see if there is any correlation as to what we've found out in this particular analyses and see if those same disparities appear.
3. With the data that we have analyzed, we can address the high cost of rides in rural areas, as well as the number of drivers in these areas. Perhaps by creating an incentive to drivers to service in these areas, there could be an increase of rides in that area. This could encourage drivers to work in rural areas, potientally decreaseing the average fare of a ride for consumers, while also increasing the number of rides, ultimately, increase revenue and enhance affordability.
