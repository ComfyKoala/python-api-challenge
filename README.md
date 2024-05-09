# python-api-challenge

This repo contains 2 modules:

1. WeatherPy
   - This module randomly selects cities around the world and retrieves current weather data from the OpenWeatherMap API.
   - It then stores that information and creates multiple scatter plots which pit Latitude against other measurements including:
     - Max Temperature
     - Humidity
     - Cloudiness
     - Wind Speed
2. VacationPy
   - This module takes the city data pulled from WeatherPy and creates two maps:
     - Map of all the cities
     - Map of cities (and nearest hotel!) that fall within 40-70% humidity and have a max temp of 29C or ~85F
