# PyBer_Analysis

**_PyBer Analysis Challenge Write-Up_**

**Overview of the Project**

For this analysis, we utilized Jupyter Notebook with Pandas and Matplotlib dependencies. The ultimate goal was to use the given data, which outlined weekly fares of rides given in different cities, classified and divided over the course of four months and based on the type of city each one was: urban, suburban, or rural. The project aimed to create various graphs and tables that outlined the weekly fares, the total number of rides given, and the number of drivers in a given city type. A line graph was then produced with the calculated results.

**Results**

*Overall*

As a whole, over the course of this period, there were a grand total of 125 rides offered in rural areas, 625 rides in suburban areas, and 1,625 rides in urban areas. It would seem that as naturally suspected, due to the larger populations in urban areas, compared to a more modest population size in suburban areas and small population size in rural areas, more rides are given in urban areas, and fewer are given in rural areas, with suburban areas having an in between value. Correspondingly, rural areas have 78 drivers, suburban areas have 490 drivers, and urban areas have 2,405 drivers. Rural areas have accumulated a total fare value of $4,327.93, suburban areas have accumulated a total fare value of $19,356.93, and urban areas have accumulated a total fare value of $39,854.38. The average fare per ride in rural areas is #34.62, the average fare per ride in suburban areas is $30.97, and the average fare per ride in urban areas is $24.53. The average fare per driver in rural areas is $55.49, the average fare per driver in suburban areas is $39.50 and the average fare per driver in urban areas is $16.57. Inversely to the total values, the average fares are cheaper in urban areas and more expensive in rural areas. This may have to do with a lower supply of drivers in rural areas relative to urban areas while the demand for rides may be relatively higher in comparison. 

![Summary Table Module 5](https://user-images.githubusercontent.com/6594718/161404092-abd421b1-98f6-47ef-bb65-6f341bbd9375.png)

*Time Trends*

In terms of how total weekly fares by city type change over the course of four months, it appears for all city types, their total fares reach their highest in mid-late February, however, rural areas reach their highest accumulated fares from rides in April. Urban areas reach a similar peak in early March. 

http://localhost:8888/files/PyBer_Analysis/Pyber_fare_summary.png

**Summary**

All in all, it seems that there are fewer drivers in rural areas, a moderate amount in suburban areas, and a high amount of drivers in suburban areas, and the corresponding number of rides given is proportional to this. The average fare per ride and driver in rural areas is incidentally more expensive than in urban areas, but the total fares accumulated in rural areas is still smaller than those in urban areas. This would suggest that for V. Isualize, there needs to be a higher number of drivers available in rural and suburban areas to accumulate more fares, and perhaps also lower the cost of rides so that more people will be compelled to take rides in suburban and rural areas, as rides in such areas are comparatively more expensive. Driver amounts should be at their highest in February and March as those seem to be the points where demand for rides is highest.
