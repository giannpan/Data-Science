# 🌦️ Weather Analysis of Athens during 2012-2023

This notebook demonstrates a simple weather analysis of data of a particular location using python. 
Here, the weather datasets are time-series data set with per-day information about the weather conditions at Athens, Greece. 
It records temperature, dew point temperature, relative humidity, wind speed, weather description etc.

 

## Datasets:

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




## Contents:

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


## Software:

⚙️Programming Language : Python

Libraries used:

1) Numpy
2) Pandas
3) SciPy
4) MatplotLib
5) scikit-learn


## Conclusions
Avg Direction of the wind
![image](https://github.com/giannpan/Data-Science/assets/119360228/895eaac0-fe55-4cdb-b429-973e57f6b5a3)
Avg speed per wind direction
![image](https://github.com/giannpan/Data-Science/assets/119360228/3fb9baf1-ddcc-42ed-af99-c169a68500bc)
Avg temperature per wind direction
![image](https://github.com/giannpan/Data-Science/assets/119360228/3fb9fb7e-1c3f-4560-85b5-43afd76c842c)
High rainfall days per year
![image](https://github.com/giannpan/Data-Science/assets/119360228/699d316f-4ede-425c-a83d-91bcdb74911e)
Total Snowy days per year
![image](https://github.com/giannpan/Data-Science/assets/119360228/e6ecb493-8141-4b5c-95f6-c76f70f63216)
Average temp per year
![image](https://github.com/giannpan/Data-Science/assets/119360228/38c5ca6e-e266-4deb-9fcb-392af3b28f8d)
Minimum,Maximum and Average temperature per Day (Each graph for each season)
![image](https://github.com/giannpan/Data-Science/assets/119360228/ffd7b55f-881c-4678-9701-0fe57ce888e7)


Scenario|Degrees Estimation|
----------|-----------|
2018|Monday     |
2019|Wednesday  |
2020|Wednesday  |
2021|Sunday     |
2022|Friday     |

