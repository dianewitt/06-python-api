### Python library and the OpenWeatherMap API to collect weather data

* Sample Python API code
    
    ```
    weather_dict = {
        "Latitude":latitude,
        "Longitude":longitude,
        "City":city_name,
        "Country":country,
        "Temperature":temp,
        "Humidity":humidity,
        "Cloudiness":cloudiness,
        "Wind Speed":wind_speed,
        "Date":date,
        "Maximum Temperature":max_temp    
    }

    weather_data = pd.DataFrame(weather_dict)
    print(weather_data.count())
    weather_data.head()
    ```

* Create scatterplots of weather data from world cities

        Latitude vs Temperature
    ![plot01](WeatherPy_output/plot01.png)
<!--         
        Latitude vs Humidity
    ![plot02](WeatherPy_output/plot02.png)

        Latitude vs Cloudiness
    ![plot03](WeatherPy_output/plot03.png) 

        Latitude vs Wind Speed
    ![plot04](WeatherPy_output/plot04.png) 
 -->

* Perform linear regression on weather data to determine maximum temperature

        Latitude vs Temperature
    ![plot05](WeatherPy_output/plot05.png)
