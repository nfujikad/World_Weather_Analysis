# World_Weather_Analysis

## Project Overview
The goal is to generate a vacation map for users where they state their weather criteria to identify potential travel destinations. The analysis utilized Google API's, in order to  provide recommendations for ideal hotels within the preferred travel destinations. 

## Resources
-   Software: Python 3.9.12 
-   Jupyter Notebooks

## Summary
The vacation map was generated bu creating a list of 1,500 random latitudes and longitudes. Using the coordinates and the citypy module, the nearest cities can be retrieved and compiled into a list. Then, a request for current weateher data is achieved with the OpenWeatherMap API. Weather from each unique city on the list is accessed. The resulting map provides users with descriptions of the destinations found on the list:
1. hotel name
2. city
3. country
4. current weather and description.