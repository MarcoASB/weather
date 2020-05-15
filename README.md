# WeatherPy :globe_with_meridians:

### "What's the weather like as we approach the equator?"

* Visualization by scatter plots of the weather of 500+ cities across the world randomly selected by coordinates (latitude and longitude) using **citipy**, to showcase the following relationships:

  * Temperature (F) vs. Latitude   :fire:
  * Humidity (%) vs. Latitude   :sweat_drops:
  * Cloudiness (%) vs. Latitude   :cloud:
  * Wind Speed (mph) vs. Latitude   :dash:
  
## Analysis: 
* As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). More interestingly, however, is the fact that the southern hemisphere tends to be warmer this time of year than the northern hemisphere. This may be due to the tilt of the earth.
* There is no strong relationship between latitude and cloudiness, however, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.
* There is no strong relationship between latitude and wind speed, however in northern hemispheres there is a flurry of cities with over 20 mph of wind.
----
* Considerations:
  * Every time you run the program, the responses will change randomly 
  * Date is retrieved in [Unix Timestamp](https://www.unixtimestamp.com)

* Tools: 
  * [Citipy Python library](https://pypi.python.org/pypi/citipy)
  * [OpenWeatherMap API](https://openweathermap.org/api)
  
  ![Equator](Images/equatorsign.png)





