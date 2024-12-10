# python-api-challenge

WeatherPy Project
Overview
The WeatherPy Project analyzes global weather patterns by pulling data from the OpenWeatherMap API and visualizing relationships between latitude and weather factors like temperature, humidity, cloudiness, and wind speed.

Repository Structure
output_data/ 
fig1.png: Latitude vs. Max Temperature
fig2.png: Latitude vs. Humidity 
fig3.png: Latitude vs. Cloudiness
fig4.png: Latitude vs. Wind Speed
cities.csv: Raw weather data
WeatherPy.py: Script to gather weather data
Vacation.py: Script to visualize data and find hotels

Instructions
Gather Weather Data: WeatherPy_part1.py fetches weather data from the OpenWeatherMap API and saves it to cities.csv.
Visualize Data: WeatherPy_part2.py generates scatter plots and performs linear regression, saving the plots to output_data/.
Map Hotels: Finds the nearest hotels for cities with ideal weather conditions and maps them.
