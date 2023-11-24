🌦️ Weather Analysis of Athens during 2012-2023

This notebook demonstrates a simple weather analysis of data of a particular location using python. 
Here, the weather datasets are time-series data set with per-day information about the weather conditions at Athens, Greece. 
It records temperature, dew point temperature, relative humidity, wind speed, weather description etc.

    ***********************************************************************************************************

Datasets:
The Datasets were downloaded from:
https://www.visualcrossing.com/
More specifically we are going to work with the following csv datasets 
athens 2012-01-01 to 2013-12-31.csv
athens 2014-01-01 to 2015-12-31.csv
athens 2016-01-01 to 2017-12-31.csv
athens 2018-01-01 to 2019-12-31.csv
athens 2020-01-01 to 2021-12-31.csv
athens 2022-01-01 to 2022-12-31.csv
athens 2023-01-01 to 2022-11-21.csv



    ***********************************************************************************************************
Contents:

    a) Concatenation of the datasets
    b) Make the extra columns for Month,Year,Concat(of month and year) 
    c) Make an extra column for wind direction
    d) Interpolation for the missing values (in tempmin and tempmax)

    a) How many days was windy and from which direction for each year 
    b) Which direction gave the maximum temp and which the minimum
    c) Which was the average temp for each direction.
    b) Compare the total amount of rain between years.
    e) Which were the top5 days with the maximum rain
    f) Find the number of the days per year that had snow
    g) Find the months that used to snow more.
    h) Compare the average temperature between years - make a visual
    i) Find the heatwaves of the last 10 years
    j) Answer the question if the planet is going warmer
    
    a) Keep only 1/10 - 31/12 for each year
    b) Find the correlation of temperature between other years and this year
    c) Find the temp of 25/12/2023 using sklearn

    ***********************************************************************************************************
Software:
⚙️Programming Language : Python

Libraries used:
Numpy
Pandas
SciPy
MatplotLib
scikit-learn



    ***********************************************************************************************************
Conclusions
