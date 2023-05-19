# python-api-challenge

## Background
The true power of data lies in its ability to provide definitive answers. In this project, we will utilize Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

To begin, create a new repository called "python-api-challenge" and clone it to your local machine. Inside the repository, create a directory named "WeatherPy" to house the main scripts for the weather analysis.

The first part of the project, WeatherPy, involves creating a Python script to visualize the weather of over 500 cities at varying distances from the equator. We will use the citipy library, the OpenWeatherMap API, and our problem-solving skills to create a representative model of weather patterns across cities.

The provided "WeatherPy.ipynb" notebook will guide you through the process and provide the necessary starter code to generate random geographic coordinates and find the nearest cities to those coordinates.

## WeatherPy - Requirements
1. Create plots to showcase the relationship between weather variables and latitude. Use the OpenWeatherMap API to retrieve weather data for the generated cities.
   - Create scatter plots to visualize the following relationships:
     - Latitude vs. Temperature
     - Latitude vs. Humidity
     - Latitude vs. Cloudiness
     - Latitude vs. Wind Speed

2. Compute linear regression for each relationship and create scatter plots for the Northern and Southern Hemispheres separately.
   - Include the linear regression line, the model's formula, and the r-value on the plots.

   Plots to be created:
   - Northern Hemisphere: Temperature vs. Latitude
   - Southern Hemisphere: Temperature vs. Latitude
   - Northern Hemisphere: Humidity vs. Latitude
   - Southern Hemisphere: Humidity vs. Latitude
   - Northern Hemisphere: Cloudiness vs. Latitude
   - Southern Hemisphere: Cloudiness vs. Latitude
   - Northern Hemisphere: Wind Speed vs. Latitude
   - Southern Hemisphere: Wind Speed vs. Latitude

   Provide explanations for the observed relationships and any additional findings.

## VacationPy - Requirements
In the second part of the project, VacationPy, we will utilize our weather data skills to plan future vacations. We will use Jupyter notebooks, the GeoViews Python library, and the Geoapify API.

The provided "VacationPy.ipynb" notebook contains the necessary code to import libraries, load the CSV file with weather and coordinate data for each city from Part 1.

Tasks for VacationPy:
1. Create a map that displays a point for every city in the city_data_df DataFrame, with the size of the point representing the humidity level.
2. Narrow down the city_data_df DataFrame to find cities with ideal weather conditions, such as a max temperature between 21 and 27 degrees Celsius, wind speed below 4.5 m/s, and zero cloudiness.
3. Create a new DataFrame, hotel_df, to store the city, country, coordinates, and humidity.
4. Use the Geoapify API to find the first hotel within 10,000 meters of each city's coordinates.
5. Add the hotel name and country as additional information in the hover message for each city on the map.

*Note: Adjust the specifications for ideal weather conditions as needed, but ensure a reasonable limit on the number of rows returned by the API requests.*

## Files
Download the following files to get started:
[Module 6 Challenge files](https://...link...)

## Instructions
1. Create a new repository called "python-api-challenge" and clone it to your local machine.
2. Inside the repository, create a directory named "WeatherPy" to house the weather analysis scripts.
3. Add the following files to the "WeatherPy
