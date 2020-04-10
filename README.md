## What's the Weather Like? ##

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

