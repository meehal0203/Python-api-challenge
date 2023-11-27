# python-api-challenge

# Part 1: WeatherPy
In this deliverable, I will create a Python script to visualize the weather of over 500 cities of varying distances from the equator. I have used the citipy Python libraryLinks to an external site and the OpenWeatherMap APILinks to an external site in order to create a representative model of weather across cities.
I have used the OpenWeatherMap API to retrieve weather data from the cities list to create a series of scatter plots to showcase the following relationships:

* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

I then separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) and computed the linear regression with analysis for the following:

* Northern Hemisphere: Temperature vs. Latitude

* Southern Hemisphere: Temperature vs. Latitude

* Northern Hemisphere: Humidity vs. Latitude

* Southern Hemisphere: Humidity vs. Latitude

* Northern Hemisphere: Cloudiness vs. Latitude

* Southern Hemisphere: Cloudiness vs. Latitude

* Northern Hemisphere: Wind Speed vs. Latitude

* Southern Hemisphere: Wind Speed vs. Latitude

 # Part 2: VacationPy
In this deliverable I used Jupyter notebooks, the geoViews Python library, and the Geoapify API to plan future vacations and create map visualizations.

I created a map that displays a point for every city in the city_data_df DataFrame and then narrowed down the DataFrame to find the ideal weather condition. For example:

A max temperature lower than 29 degrees but higher than 20

Wind speed less than 5.5 m/s

Zero cloudiness.

I then used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates and added the hotel name and the country as additional information in the hover message for each city on the map.


Sources: For this particular project I used Stack Overflow, BCS Learning Assistants and had a tutoring session which helped me get this all squared away.

