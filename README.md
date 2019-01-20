# Weather_Py
In this example, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a citipy and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

The objective was to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

My final notebook includes:

* Randomly selected 500+ unique (non-repeat) cities based on latitude and longitude.
* A weather check on each of the cities using a series of successive API calls.
* A print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

Analysis was done using a Jupyter notebook.
Matplotlib and Pandas plotting libraries were used for scatter plots.
A written description of three observable trends based on the data is included.
