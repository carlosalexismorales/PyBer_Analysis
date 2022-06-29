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

As shown in the image below, it appears that riders in suburban areas pay on average almost $10 less for PyBer than riders in rural areas. The average fare per ride is approximately $25 in suburban areas, compared to the average fare per ride of $35 in rural areas. The average fare per ride for Suburban areas lands between the previous two at around $31. While this is an indication that rides in rural areas are more costly than elsewhere, we would need more data to interpret as to why this may occur. One piece of data that does give some context to this obversation is the average fare per driver. In rural areas, we see that this particular area has the highest average of fare per driver at around $55. In urban areas, it is around $40 and in suburban, it is about $17. This indicates that consumers are paying more for drivers in rural areas than anywhere else. This could be because of the amount of riders that are in each of these areas. To clarify, we see that the image below illustrates that there are only 78 drivers in rural areas compared to the 2,405 drivers in urban areas. Given that there is a greater usage of PyBer in urban areas, the total fares are consequently also higher than suburban and rural areas. PyBer transactions in urban areas totaled nearly $40,000 whereas transactions in urban areas and rural areas totaled at least $19,000 and $4,000, respectively. This is a major difference that can provide context as to why there aren't as many rides or drivers in rural areas. Again, this can be due to the density of the population and destination locations in those areas, with locations usually being farther in rural/countryside areas than urban or suburban ones, but we would need more data to have a deeper understanding of this. 

