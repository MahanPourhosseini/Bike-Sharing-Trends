### Problem Statement
With environmental issues and health becoming trending topics, usage of bicycles as a mode of transportation has gained traction. To encourage bike usage, cities across the world have successfully rolled out bike sharing programs. Under such schemes, riders can rent bicycles using manual/automated kiosks spread across the city for defined periods. In most cases, riders can pick up bikes from one location and return them to any other designated place. The bike sharing platforms from across the world are hotspots of all sorts of data, ranging from **travel time**, **start** and **end location**, demographics of riders, and so on. This data along with alternate sources of information such as **weather**, **traffic**, and so on makes it an attractive proposition for different research areas. The goal of this session is to predict the count of bike rental demand. To this end, we use bike sharing dataset with **weather information**.

### Bike riding dataset description
* The dataset contains more than 17k samples with 17 attributes
  * record index
  * date
  * season : season (1:Spring, 2:Summer, 3:Fall, 4:Winter)
  * year (0: 2011, 1:2012)
  * month ( 1 to 12)
  * hour (0 to 23)
  * holiday : whether day is holiday or not
  * weekday : day of the week (0 to 6)
  * workingday : if day is neither weekend nor holiday is 1 otherwise is 0
  * weather_condition:
    
		- 1: Clear, Few clouds, Partly cloudy
    
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
  * temp : Normalized temperature in Celsius. The values are divided to 41 (max)
  * atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
  * humidity: Normalized humidity. The values are divided to 100 (max)
  * windspeed: Normalized wind speed. The values are divided to 67 (max)
  * casual: count of casual users
  * registered: count of registered users
  * total_count: count of total rental bikes including both casual and registered
