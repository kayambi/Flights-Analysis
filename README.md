# Flights-Analysis


I. Objective:  In this Analysis , I will explore in depth about flight delay by predicting the delay, my target here is departure_delay.  
I will also try to use a front end-interface for models.  

II. Data

1. [x] Write an API to download data straights from from the website
2. [x] Write an API to source airports data: location and ranking
3. [x] Build database of flights, airports and airlines

III. Data Cleaning and Munging

1. Combine tables
2. Treat missing values
3. Create new features: 
    - Days_to_Holiday: how many days is a day to the closest holiday
    - Rec_Time: time recovered on departure and arrival delay time
    - Normalize delay times with respect to Airtime

IV. Hypothesis

Flights delays may be influenced by

- date (year, month, day of the month, day of the week, week of the year)
- local time (ArrTimeBlk / DepTimeBlk)
- origin airport
- destination airport
- airline
- Furthermore, historical data on flight delays may be informative about future delays. For instance, weather related reasons of delays last year may occur again this year within the same period of the year

V. Exploratory data analysis Here, we shall explore available data to validate our hypothesis.