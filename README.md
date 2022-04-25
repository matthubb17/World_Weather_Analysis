# World_Weather_Analysis

## Project Overview:

The goal of this project was to help PlanMyTrip, a top travel technology company, to collect and analyze weather data across cities worldwide.

## Resources:

**Data Source (Folders):** [Weather_Database](https://github.com/matthubb17/World_Weather_Analysis/tree/main/Weather_Database), [Vacation_Search](https://github.com/matthubb17/World_Weather_Analysis/tree/main/Vacation_Search), [Vacation_Itinerary](https://github.com/matthubb17/World_Weather_Analysis/tree/main/Vacation_Itinerary)

**Challenge Files:** [Weather_Database](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), [Vacation_Search](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb), [Vacation_Itinerary](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb) 

**Software:** Python 3.9.7, Jupyter Notebook

## Overview:

### Weather Database:

In this section we pulled weather information using an api call from the OpenWeatherMap. This data included information for over 600 random cities.

This info contains:

  - Latitude and longitude
  - Maximum temperature
  - Percent humidity
  - Percent cloudiness
  - Wind speed
  - Weather description (for example, clouds, fog, light rain, clear sky)

![DF](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Weather_Database/City_Data_DF.png)


### Vacation Search:

In this section we created a customer travel destination map to identify potential travel destinations and nearby hotels. We then plotted these destinations on a marker layer map with pop-up markers.

![WeatherPy_vacation_map](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)


### Vacation Itinerary:

In this section we created a travel itinerary map that shows the route between four cities chosen from the customer's possible travel destinations. 

![WeatherPy_travel_map](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

Then we created a marker layer map with a pop-up marker for each city on the itinerary.

![WeatherPy_travel_map_markers](https://github.com/matthubb17/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
