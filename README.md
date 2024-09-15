# python-api-challenge



## Table of contents

* [Description](#Description)
* [Part 1 WeatherPy](#Part-1-WeatherPy)
* [Part 2 VacationPy](#Part-2-VacationPy)
* [Outpu Images](#Outpu-Images)
* [Questions](#Questions)
* [References](#References)

## Description

For this challenge we will create a Python script to visualize the weather of over 500 cities of varying distances from the equator. This challenge is going to use Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

While the obvious answer is: it gets hotter. But, if pressed for more information, how would you prove that?

## Part 1 WeatherPy

In this part we will create a Python script to visualise the weather of over 500 cities of varying distances from the equator.

1. Generate random geographic coordinates and find the nearest city to each latitude and longitude combination using the citipy Python library.
2. Then, the OpenWeatherMap API is used to retrieve waether data for each city.
3. Create a series of scatter plots to display the following relationships:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

4. Separate the plots above into Northern and Southern hemispheres, then calculate the linear regression for each.


## Part 2 VacationPy

In this part we will use the weather data from Part 1 to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point indicates the humidity in each city.
2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

* A max temperature lower than 27 degrees but higher than 21
* Wind speed less than 4.5 m/s
* Zero cloudiness
* the main objective is to limit the dataframe to 10-20 rows.
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city in the map.

## Outpu Images

![Fig1](/WeatherPy/output_data/Fig1.png)
![Fig2](/WeatherPy/output_data/Fig2.png)
![Fig3](/WeatherPy/output_data/Fig3.png)
![Fig3](/WeatherPy/output_data/Fig4.png)

## Questions

In case of any additional questions please visit my GitHub link: [Feda2020](https://github.com/Feda2020) 

## References
 
 * Xpert Learning (https://bootcampspot.com)
 