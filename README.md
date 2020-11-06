# Meteoservice

An educational application with which you can get information about weather.
Implemented in Ruby.
Application use [meteoservice.ru](https://www.meteoservice.ru) to get xml with a data.

Language Russian.

## Requirements

ruby '2.4.0' or higher

## Getting started

Run meteoservice.rb
```
ruby meteoservice.rb
```

## Adding a city

You can add city id from [meteoservice.ru](https://www.meteoservice.ru/content/export.html)

Fill in the hash in the meteoservice.rb as in the example 

	CITIES = {
	  37 => 'Москва',
	  69 => 'Санкт-Петербург',
	  99 => 'Новосибирск',
	}.invert.freeze
 