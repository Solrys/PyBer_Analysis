# PyBer Analysis
Analysis for rideshare using Matplotlib

## Method
Jupyter Notebook
Pandas

## Background

Pyber is a python based ride share app company. We will be looking at the relationship between three city types, Urban, Suburban, and Rural and comparing the number of drivers and rides and fares. This data study will help us improve access, eficiency, and affordabilty. This data covers January to early May of 2019. 

I used Jupyter Notebook and Panda script to inspected data from large csv files. I then merged data sets, and performed several calculations. With Matplotlib, I created visual two dimensional graphs to better understand and analyze the Pyber rideshare outlook. Looking at the visual story through various graphs has helped bring this analysis to life by offering an easy way to understand apects of rideshare in comparison, and helped visulaize patterns, corelations, and trends.  


## Analysis

Pyber has established a presence in Urban, Suburban and Rural cities. Looking at the data I found that the number of rides, drivers and average fare varies for each of those city types.

I created a Bubble chart highlighting the following aspects. 
* Average Fare ($) Per City
* Total Number of Rides Per City
* Total Number of Drivers Per City
* City Type (Urban, Suburban, Rural)

![bubble_1](https://github.com/Solrys/PyBer_Analysis/blob/main/resources/Screen%20Shot%202020-12-20%20at%208.28.32%20PM.png)

#### From this chart we can clearly see the corelation between driver count and fare. Urban cities had the largest driver count while Rural and Suburban cities were able to command the largest average fare. 


Next I analyzed the following information and created a visual representation with the use of charts:
* % of Total Fares by City Type
* % of Total Rides by City Type
* % of Total Drivers by City Type

![plot](https://github.com/Solrys/PyBer_Analysis/blob/main/resources/Screen%20Shot%202020-12-20%20at%208.29.09%20PM.png)


![pie1](https://github.com/Solrys/PyBer_Analysis/blob/main/resources/Screen%20Shot%202020-12-20%20at%208.29.42%20PM.png)


![pie ](https://github.com/Solrys/PyBer_Analysis/blob/main/resources/Screen%20Shot%202020-12-20%20at%208.30.20%20PM.png)

#### In the charts above there is a clear correlation between higher percentage in each of the aspects measured and city size. Urban cities had the highest percentage of total fares, total rides, and total drivers, while the rural cities had the smallest percentage.  

Next I created a DataFrame column to get the total number of rides, total number of drivers, and the total fares for each city type. Then, I calculated the average fare per ride and average fare per driver for each city type. Finally, I added this data to a new DataFrame, then format the columns as shown below:

![Columns](https://github.com/Solrys/PyBer_Analysis/blob/main/resources/Screen%20Shot%202020-12-20%20at%209.29.43%20PM.png)

![line](https://github.com/Solrys/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

#### Here we see that the less populated rural cities had the highest average fare but the urban cities brought in the most income overall. 








## Conclusions and Recomendations
Even though less populated rural and suburban cities were able to bring in a highe average ride share fare, there were more total rides in the urban cities indicating the urban cities are more lucrative. There are other aspects of this data we would need to gather to get a clearer picture.Some questions remain:
* How long do drivers wait in between rides for the three city types. 
* Where are competitors in respect to the three city types and how does that compare to average fares. 
* Is the higher fare average a result of less competition?
* What is the overall picture for the entire annual year?

The data we collected can possibly help the company PyBer increase revenue by understanding where to allocate drivers and when to demand higher fares or when to offer competititve rates. 



