# PyBer_Analysis

## Overview of Analysis

### Summary of the request

I'm a new data scientist for PyBer and my manager, Omar, has tasked me with analyzing all the rideshare data from January to late April of 2019 and creating a compelling visualization for the CEO of PyBer, V. Isualize. V. Isualize specifically wants to see a multiple-line graph that shows the total weekly fares for each city type and wants to know how the data differs per city type. It's my job to deliver a sound analysis, stunning visual, and a few business recommendations based on that data.

### Data Sources and software
I was provided with two .csv's full of data: [city_data.csv](https://github.com/kylebrumbaugh9/PyBer_Analysis/files/10061909/city_data.csv) and [ride_data.csv](https://github.com/kylebrumbaugh9/PyBer_Analysis/files/10061912/ride_data.csv)

I used Jupyter Notebook, Python 3.7, pandas, matplotlib, and the fivethirtyeight graph style in order to complete this project. I also used pandas.pydata.org and stackoverflow.com to answer some of my questions along the way

## Results of PyBer Analysis

![highlighted_first_3_columns](https://user-images.githubusercontent.com/114685724/203198775-7d33e177-fd7a-41cd-b2a9-ba8d5f5bfa99.jpg)


After wrangling the data, I was able to build a summarized data frame (shown above) that allowed me to see differences between the types of cities at a glance. It's pretty easy to see the main differences across the board, but to summarize the differences in a word: volume. The urban market saw 2.6 times more rides than the suburban market and 13 times more rides than the rural market. Similarly, urban markets saw double the sales of suburban markets and actually had nearly 5 times as many drivers than suburban markets. All of this shows that the urban markets gave far more rides, made far more money, and had far more drivers available. To see the sum of fares broken down per week, see the visual below.

![Total_Fare_By_City_Type](https://user-images.githubusercontent.com/114685724/203197673-062b88ea-4360-4cef-b163-0c0668195c51.png)


![highlighted_last_2_columns](https://user-images.githubusercontent.com/114685724/203198831-08fe715f-42cc-40ea-8410-d2f350034810.jpg)


On the other hand, the rural markets had far higher average fares per ride and average fares per driver than both the suburban and urban markets. While the spread of between average fares per ride was only about $10, the average fare per driver had a spread of almost $40! 

One final point to make was that is appears that the urban market is flooded with drivers; there are more drivers than rides in the urban cities! With 2,405 drivers and only 1,625 rides, this means that the odds are there were hundreds of drivers that never provided a ride during the 4 months of data I analyzed. It means that every driver gave about 0.67 rides over those 4 months. Conversely, suburban drivers gave about 1.27 rides and rural drivers 1.60 rides during the same time period.


## Summary of Analysis

I think this data shows a few things.
1. Urban markets are flooded with drivers so we should not focus on hiring more drivers in urban areas. The only reason we would want to hire more drivers is if wait times are annoyingly high for our riders; I would want to complete further analysis to look at wait times but given this data, we should place a hiring freeze within the urban markets if we're paying our employees per hour. 
2. We get more "bang for our buck" if we can increase the number of rural rides we give. Those fares run much higher and it works out well for the driver as well, so it shouldn't be too difficult to convince rural drivers to come on board. They're going to make a lot of money! The average fare is 40% higher than urban markets and almost 12% higher than suburban markets, so growing this part of our business would be beneficial. Since the lack of rides probably stems from a lack of drivers, we should focus on hiring more drivers in the rural markets. 
3. Suburban rides are the sweet spot so we should really give a lot of focus to suburban rides. The dropoff on number of rides is precipitous from urban to suburban and again from suburban to rural, but if we can shorten the gap between urban and suburban, this will increase our total fares drastically. There isn't a huge dropoff in average fare from rural to suburban but there is a large dropoff in average fare from suburban to urban. To put it another way, if we could increase the number of suburban rides by 1,000 to equal the number of urban rides but keep the same average fare, suburban fares would total over $50,000! So suburban fares would earn $11,000 more than urban on the same number of rides. 

Overall, to summarize again:

1. Don't hire any more urban drivers
2. Increase the number of rural drivers
3. Increase the number of suburban rides and drivers
