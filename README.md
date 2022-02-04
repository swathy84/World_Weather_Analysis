# World_Weather_Analysis



## Purpose
The main purpose of this project is to collect and analyze weather data across cities worldwide to help PlanMyTrip company to use the analyzed data to recommend ideal hotels based on clients weather preferences.

### Initial Analysis
The initial analysis of the data will be split in 3 main parts .
•Collect the Data
•Exploratory analysis with visualization
•Visualize the Travel data

[WeatherPY](WeatherPy.ipynb)
[VacationPy](VacationPy.ipynb)

### Updated Analysis 
The purpose of the updated analysis is to create a vacation map that allows user to apply weather criterias to identify travel destination places. Using Google APIs,we were able to provide the user with recommended ideal hotels within their preferred destination places

Click here to view the files - [Weather_Database](Weather_Database),[Vacation_Search](Vacation_Search),[Vacation_Itinerary](Vacation_Itinerary)  

## Overview
In order to create vacation map, we generated 2000 random latitudes nad longitudes.With coordinates we retrieved and combined list of the nearest cities using the citipy module. Then, we used OpenWeatherMap API to collect the data related to weather from each unique city from the list. The map provided users with descriptions of the destination places found on the list ,including hotel name,city,country and current weather description.