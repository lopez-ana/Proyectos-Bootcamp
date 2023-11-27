
# Autoras
=========================================

Andrea cabrera, Catalina Tomás Jaume, Lourdes Boj, Ana Isabel López Navarro


# Descripción
=========================================	

GoGreen Bikesharing es una empresa de Whashington D.C. dedicada al alquiler de bicicletas.

El dataset sobre el que trabajamos posee datos tales como la cantidad de bicis alquiladas por usuarios registrados, la cantidad de alquileres realizados por usuarios puntuales, y la cantidad total. A estos datos se les añadió información meteorológica, y el calendario de festivos.

En este proyecto se van a analizar cuáles son los aspectos que más influyen en la cantidad de bicis que se van a alquilar en un día.

También se harán varios modelos de Machine Learning que nos permitan realizar predicciones de cuántas bicicletas se van a alquilar en un día.


# Variables Dataset 
=========================================	
	
	- instant: record index
	- dteday : date
	- season : season (spring, summer, autumn, winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered


# Estructura
=========================================	

En este repositorio se encuentran tres carpetas:

- 'data': archivos generados 
- 'graficas' : imágenes de las gráficas
- 'notebooks': archivos jupyter donde se ha realizado el EDA, los modelos de predicción y las predicciones.
