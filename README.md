# python-api

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: "Duh. It gets hotter..."

But, if pressed, how would you prove it?

Part I - WeatherPy
Using a python library, the openweather API i create a representational model of the weather across 500 cities.
The relationships showcased are:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
![weather](https://github.com/Lizbetheli/python-api-challenge/blob/master/Images/Latitudeandcloudiness.png?raw=true)


Then i ran linear regressions on the following:

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude
![weather](https://github.com/Lizbetheli/python-api-challenge/blob/master/Images/Southtwindandlat.png?raw=true)
Part II - VacationPy
Heatmap for weather in 500+ cities
with markers for recommended hotels
