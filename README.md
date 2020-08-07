## What's the Weather Like? Analysis

**Part I - WeatherPy**

**Research question: "What's the weather like as we approach the equator?"**

Will show a series of scatter plots to showcase the following relationships to visualize the weather of 500+ cities across the world of varying distance from the equator:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

**Findings and Observations**
- Temperature (F) vs. Latitude: Data shows that the closer the latitude is to 0°, the higher the temperature

- Humidity (%) vs. Latitude: Data shows that there is no correlation visible

- Cloudiness (%) vs. Latitude: Data shows that there are pockets where there is a maximum percent of cloudiness and zero percent of cloudiness. About 0 percent of clouds were areas with a 20° to 60° latitude range and high maximum cloudiness percent were areas with -20° to 0° and 40° to 70° latitude range.

- Wind Speed (mph) vs. Latitude: Data shows that there is no correlation visible. However there was an outlier for maximum wind speed around 70° latitude for the random data set that included this data point.


Next will show a series of scatter plots with a linear regression of the same cities but showcasing the following relationships according to the Northern Hemisphere and Southern Hemisphere

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude

- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude

- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude

- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

**Findings and Observations**

- Northern and Southern Hemisphere - Temperature (F) vs. Latitude:  There is a strong to moderate correlation between Latitude coordinate and Temperature. The closer to the equator(0°) the higher the temperature, the further away from the equator temperature decreases.

- Northern and Southern Hemisphere - Humidity (%) vs. Latitude: There was a weak to no correlation between Latitude coordinate and Humidity.

- Northern and Southern Hemisphere - Cloudiness (%) vs. Latitude: There was a weak to no correlation between Latitude coordinate and Cloudiness. However, there are pocket areas where there were a maximum percent of cloudiness between 0° to -20° in the Southern Hemisphere and 60° to 70° in the Northern Hemisphere.

- Northern and Southern Hemisphere - Wind Speed (mph) vs. Latitude: There was a weak to no correlation between Latitude coordinate and Wind Speed. However, there was an outlier that had the maximum wind speed which was Lakselv, Norway at around 70° latitude for the random data set that included this data point.

**Part II - VacationPy**

**Research Goal: Working with weather data to plan a future vacation with a weather preference**

Will show the following below:
- A heat map that displays the humidity for every city from the Part I - WeatherPy
- A DataFrame that finds ideal weather conditions for some place with the maximum temperature lower than 80 degrees F, minimum temperature of 60 degrees F, wind speed less than 10 mph, and humidity lower than 45%
- A heat map that displays the humidity for every hotel and a pin containing the Hotel Name, City, and Country located within 5000 meters of city coordinates with the ideal weather conditions from above

---
## What's the Weather Like? Instructions

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?


## Part I - WeatherPy

In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

Your first objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot add a sentence or too explaining what the code is and analyzing.

Your next objective is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots explain what the linear regression is modelling such as any relationships you notice and any other analysis you may have.

Your final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.

### Part II - VacationPy

Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment.

* **Note:** if you having trouble displaying the maps try running `jupyter nbextension enable --py gmaps` in your environment and retry.

* Create a heat map that displays the humidity for every city from the part I of the homework.


* Narrow down the DataFrame to find your ideal weather condition. For example:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

  * **Note:** Feel free to adjust to your specifications but be sure to limit the number of rows returned by your API requests to a reasonable number.

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.



### Copyright

Trilogy Education Services © 2019. All Rights Reserved.


