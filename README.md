# api_challenge
Python APIs Homework

In this project I use python and the openweather api to get weather trend data on a 500+ cities across the world at varying distances 
from the equator.

My code does the following:
```
-Randomly selects at least 500 unique cities based on latitude and longitude.
-Performs a weather check on each of the cities using a series of successive API calls.
-Includes a print log of each city as it's being processed with the city number and city name.
-Saves both a CSV of all data retrieved and png images for each scatter plot.
```

With this I made a series of scatter plots to visualize the following relationships:
```
-Temperature (F) vs. Latitude
-Humidity (%) vs. Latitude
-Cloudiness (%) vs. Latitude
-Wind Speed (mph) vs. Latitude
```
