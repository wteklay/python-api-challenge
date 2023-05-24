# python-api-challenge

## WeatherPy

A Python script to visualzie the weather of over 500 cities of varying distances from the equator was created. Scatter plots to showcase the relationship between Weather Variables and Latitude was generated to showcase the following relationships:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

Next, a linear regression for each realtionship was computed for the Northern and Southern Hemisphere. 

## VacationPy

Geoapify API and the geoViews Python library was employed to create map visulaizations of humidity for every city in the DataFrame. DataFrame was narrowed down to only include ideal weather conditions such as:

* Max temperature lower than 20 degress but higher than 38
* Wind speed greater than 4.5 m/s
* Greater than zero cloudiness

Lastly, a new DataFrame was created to store the city, country, coordinates, and humidity of the filtered DataFrame. Hotel names were also amended using Geoapigy API to locate the first hotel within 10,000 meters of the coordinates. No hotels were found within 10,000 meters of the coordinates with conditions listed above. 
