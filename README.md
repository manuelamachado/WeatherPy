## What's the Weather Like?

## WeatherPy

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Utilized a [simple Python library](https://pypi.python.org/pypi/citipy), and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

### Built a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

### Analyzes:

* Randomly selected **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Performed a weather check on each of the cities using a series of successive API calls. 
* Included a print log of each city as it's being processed with the city number, city name, and requested URL.
* Saved both a CSV of all data retrieved and png images for each scatter plot.

### Applications & Tools:

* Used the Matplotlib and Seaborn libraries.

# Results and Conclusions:

After review of 688 unique cities, the data showed a pattern with average temperature with respect to latitude only.

1. As expected, as you move closer to the equator, the average temperature rises in what appears to be a parabolic trend with the apex at the equator (0 degrees latitude).  

2. Cloudiness, humidity and wind speed do not appear to have high correlations with latitude.  

3. Should we do additional testing, I would want to pull more cities from the Southern Hemisphere (30% of cities) as my current dataset includes more cities from the Northern Hemisphere (70% of cities).



