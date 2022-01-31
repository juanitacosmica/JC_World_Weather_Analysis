# JC_World_Weather_Analysis
Module 6, Exploring APIs for the first time!

# Overview of the Project:

We love the PlanMyTrip app, this project will be recommending an itinerary based on the temperature preferences of our users. We will retrieve Weather Data, Create a Customer Travel Destinations Map and a Travel Itinerary! 

# Resources:
 
 **Data source** All data used in this analysis is in the [Repo](https://github.com/juanitacosmica/JC_World_Weather_Analysis).

 **Software** Python 3.7, Anaconda 4.11.0, Jupyter Notebook, Matplotlib, API keys and Pandas.

# Results:

Using the random function, data from 2,000 latitudes/longitudes was gathered and put in a csv file, to therefore, being able to make an API call and get the weather for the nearest cities to those coordinates. This will give us a list with data such as: latitude and longitude, max temperature, % humidity, % of clouds, wind speed and a current weather description. 

![Data Summary](/Resources/img1.png)

According to the choices the user makes in terms of weather temperature, the map showcases the optional cities with markers:

![Vacation Map](/Vacation_Search/WeatherPy_vacation_map.png)

And then the magic happens! We use the Google Directions API, and we create an ideal itinerary to meet our users ideals of a perfect weather trip, they get to choose between a driving, cycling or walking route, this below is an example of a driving trip in south america:

![Vacation Map](/Vacation_Itinerary/WeatherPy_travel_map.png)

![Vacation Map](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)