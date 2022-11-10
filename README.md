# surfs_up
Use Python, SQLite to run analysis on weather data

## Overview
In this project I was given a SQLite weather database on a city in Hawaii. Using this database I used a number of dependencies to generate queries regarding the weather database. After finding the precipitation and temperatures for certain months, I am able to present these findings to investors who would like to open an ice cream and surf shop in Hawaii. This will give investors a better idea at weather conditions throughout the year and decide if this will be a proper location for their venture. 

## Results
From the analysis gathered, I was able to plot a graph representing the yearly temperature of the city of Oahu (see graph below).
![tobs](https://user-images.githubusercontent.com/112291075/201227195-2b8801e0-a178-4696-9ccf-a99d26abbead.jpg)

These temperatures seem ideal for cold ice cream and surfing weather year-round, with the lows in the 60's, high in the 80's and average in the mid 70's. +

Later I was able to take a closer look at individual months of the weather data by running queries for the months of June in the middle of the year and December the last month of the year.

**Here are the graphs:**

![June_temps](https://user-images.githubusercontent.com/112291075/201227785-1b950276-564b-4ee3-bf87-d8c1b708e6ab.jpg)
![December_temps](https://user-images.githubusercontent.com/112291075/201227797-c0f072c9-d58f-43f7-ad54-506f5b02bed0.jpg)

* Based off of this data I can present to the investors that the temperatures do not deviate that much throughout the year since the mean is between 70 and 75 degrees.
* There are no significant differences between June and December that would detract surfers from hitting the beach.
* This temperature data is also ideal for ice-cream since it is not too cold to not have it or too hot that customer's would not enjoy their treats before it melts.

## Sumamry
Based off of the weather data I was able to determine that the temperature in Oahu is consistent throughout the year. Therefore, It is safe to assume that the ice-cream and surf shack would be a safe venture to invest in. I even had the chance to make a flask app to present to investors so they easily navigate the data themselves and query dates to see the statistics for that date range. 
