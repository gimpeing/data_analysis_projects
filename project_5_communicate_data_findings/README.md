# Citi Bike Bike Share Data Exploration

## Dataset

New York city launched [Citi Bike](https://www.citibikenyc.com/how-it-works), the largest bike share program in the United States, in May 2013. It is now with 14,500 bikes and 950 station across Manhattan, Brooklyn, Queens and Jersey City. It was designed for quick trips with convenience in mind, and it's a fun and afforadable way to get around the town.

The data available for download via the [system data](https://www.citibikenyc.com/system-data) includes information about individual rides made in the bike-sharing system like trip duration, start and end station, user type, gender and etc.


## Summary of Findings

In the exploration, I found that Covid-19 pandemic and response from local governments had a big impact on the trend of the bike-share ridership in the city. 

In year 2019, the total ridership has positive relationship with season weather. Winter month (Dec - Feb) are with lowest ridership and the number picking up in Spring (Apr - Jun) and Summer (Jul-Aug). Ridership turns to downward trend during Autumn when the temperature reduces. The bike usage per day is following similar trend, with min point in Feb (2.5 rides/bike) and peak in Aug-Sep (4.2 rides/bike). Among the two groups of user type, Subscriber (annual membership, I believe typicall NYC Resident) is the majority user, consisting of 89.6%. This group of user has shorter trip duration, on average 7.6 min compared to if user is Customer(1-day pass or 3-day pass, I believe typically tourist), on average of 20.6 min. Busy hour with high riderships happens in 8-9am and 5-7pm, and more riderships during weekdays compared to weekend. The top popular route is Hamilton Park to Grove St Path. Peak age group of the riders are from early 30 years-old, and majority is male rider (71%).  

In year 2020, total ridership plummeted from March onwards, as NYC in state wide lockdown restriction from 22 March. The ridership hit lowest point in Apr and slowly picking up starting May. Ridership trend was changed. Total single trip duration increased almost doubled. Overall share of Customer user type increased from 10.4% in 2019 to 31.1%. Busy hour with high rederships no longer happens in 8-9am, but in 5-7pm instead, and more riderships during weekends instead. The top popular route change to round trip, with Liberty Light Rail top the list. Peak age group of riders remain from early 30 years-old (same as in 2019) and majority is still male rider (59%). The reduced in male ridership is mainly contributed by increased in unknown gender rider in 2020.

Several trend will changed depending on the rider's user type, whether they are Subsciber or Customer. Subscriber typically has shorter trip duration, higher frequency ride in weekdays, and during 8-9am and 5-7pm, popular route is none round trip (different start and end station). Customer give the opposite trend. In 2020, the ridership shifted towards the trend of Customer user. This trend is due to the surge in Customer user (from 41782 for the whole year of 2019 to 92930 within the 10 months of 2020). For year 2019 data, my assumption was Customer user is typically tourist. However, in year 2020, during the Covid-19 pandemic, in general people have been travelling less with stay-at-home orders and limited business operations in placed. Thus, the Customer riders in year 2020 is less likely to be the tourist from other state or foreign country. This might be new normal trend of people choosing to travel with more personal form of public transport solutions such as bicycles, scooters. 


## Key Insights for Presentation

For the presentation, I focus on ridership trend changes from 2019 to 2020 with key influence of the change in user type. I start by introducing the total ridership by year and next illustrate the change of total ridership by month between 2019 and 2020. 

Afterwards, I introduce user type trend changes from 2019 to 2020 by showing the stacked bar chart of the overall yearly number. Next, I showed the detailed change by month, by faceting the count plot by year. Then, I analyzed the variables that their trend will changed if user type differ.

First variable is the trip duration, where I will show the trip duration histrogram faceting by months for each year.   
Next is the frequency of ridership by day of week and time of day.    
Finally, I will shows the popular route change from non round trip to round trip.
These are the trend varies due to different user type, and we saw major surge in the number of Customer user in 2020. 

With the impact of Covid-19, rising number of non tourist Customer user might be a new normal trend of NYC resident mode of transportion choice. 



