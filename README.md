# python-api-challenge - What's the Weather Like?

## Part I - WeatherPy

I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this,  I utilized a simple Python library and  the OpenWeatherMap API to create a representative model of weather across world cities.

The final notebook contains:

* Randomly selected **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* A weather check on each of the cities using a series of successive API calls.
* A print log of each city as it's being processed with the city number and city name.
* Saved CSV of all retrieved data and a PNG image for each scatter plot.
* A written description of three observable trends based on the data.

## Part II - VacationPy

I created a Python script that generated a heat map that displays the humidity for every city from Part I.  To accomplish this,  I utilized  jupyter-gmaps and Google Places API to find the first hotel for each city located within 5000 meters of my coordinates and plotted the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

### Api key istructions

Below is the link to generate and add the corresponding keys for this project:
google api_key = https://console.cloud.google.com/apis
weather_apiKey = https://openweathermap.org/api