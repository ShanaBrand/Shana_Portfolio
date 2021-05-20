# Shana_Portfolio
showcase of projects completed

# Project 1 : What's the Weather Like?
In this project, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities. My final notebook included:
* Random selection of **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Weather check on each of the cities using a series of successive API calls.
* Print log of each city as it's being processed with the city number and city name.
* Saved both a CSV of all data retrieved and png images for each scatter plot.

I built a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude
