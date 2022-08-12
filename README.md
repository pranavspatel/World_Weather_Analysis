# World_Weather_Analysis

Vacation itenary: https://github.com/pranavspatel/World_Weather_Analysis/tree/main/Vacation_Itinary
vacation search: https://github.com/pranavspatel/World_Weather_Analysis/tree/main/Vacation_Search
weather database: https://github.com/pranavspatel/World_Weather_Analysis/tree/main/Weather_Database

 ## Purpose
The purpose of this analysis is to create a vacation map that allows users to apply weather criteria to identify potential travel destinations. By utilizing Google API's, we also provide the user with recommended ideal hotels within there preferred travel destinations.

## Overview
In order to create the vacation map, we generated a list of 2000 random latitudes and longitudes. With the coordinates, we retrieved and compiled a list of the nearest cities using the citipy module. Then, we used the OpenWeatherMap API to request the current weather data from each unique city on the list. The resulting map provides users with descriptions of the destinations found on our list, including: hotel name, city, country, and current weather and description.




