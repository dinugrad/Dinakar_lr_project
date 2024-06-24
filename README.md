# BoomBikes Project
. The BoomBikes is bike rental company, two years data is provided to predict the factors that would help companies growth after the Covid situtaion


## Table of Contents
* Jupiter note book 
* Python language, 
* Build a model that could help business growth
* 


## General Information
- Boombike is a rental company that rent out bikes for both registered  and casual bike riders 
- we are trying to solve the problem by building a linear model to analyze the factors or dependent variable that can help to us bring the business back  to the companies sustainability
- What is the dataset that is being used?
day.csv have the following fields:
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
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



## Conclusions
- aTemp , Season_Winter, Month_September  are the most contributing factors for the business

## Technologies Used
-  numpy 
- pandas 
- matplotlib 
- seaborn 
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@dinuGrad] - feel free to contact me!



