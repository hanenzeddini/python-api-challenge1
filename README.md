# python-api-challenge
## Project Description

-  The goal of this project is to utilize the [CitiPy Python Library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.
- Then, create a series of scatter plots to showcase the following relationships:
* Temperature vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude
- Then, run linear regression on each relationship. This time, separate the plots into Northern Hemisphere and Southern Hemisphere:
* Northern Hemisphere - Max Temperature vs. Latitude
* Southern Hemisphere - Max Temperature vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
- Using the data from the first half of this project, then create a Geoview that displays the humidity for every city from Part I.
- Finally, narrow down the DataFrame to find the "ideal" weather condition, use GeoApify API to find the first hotel for each city located within 10000 meters of the coordinates and plot the hotels on top of the Geoviews with each pin containing the **Hotel Name**, **City**, and **Country**.


## Languages & Technology Used

- Python
- Pandas
- Matplotlib
- Hvplot
- Jupyter Notebook
- CitiPy
- Open Weather Map API
- GeoApify API
