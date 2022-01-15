# World_Weather_Analysis

## Purpose
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip through PlanMyTrip app. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

## Weather Database
This will show 2000 random latitudes and longitudes, retrieve the nearest city and perform API call with the OpenWeatherMap. This also gives the current weather descriptions for each of the city.

## Vacation Search
Input statements are used to retrieve the customer weather preferences and then it is used to identify potential travel destinations and nearby hotels.

For eaxample: 
![VacationSearch](Vacation_Search\WeatherPy_vacation_map.png)

## Vacation Itinerary
With the google direction API, a travel itenary can be created that shows the route between four cities chosen from the customer's possible travel destinations.

For eaxample: 
![VacationItinerary](Vacation_Itinerary\WeatherPy_travel_map.png)