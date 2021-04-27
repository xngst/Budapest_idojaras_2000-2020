
### Data Description:

The data used for the analysis comes from [darksky.net](https://darksky.net/) and has been extracted through the [Darksky API](https://darksky.net/dev).

> (In 2020 Q1 Apple Inc had [aquired](https://edition.cnn.com/2020/03/31/tech/apple-dark-sky/index.html) darksky.net. Shortly after the aquasition, Apple announced that every darksky.net connected application and the API will be [shut down](https://blog.darksky.net/) effetctive from 2021). There is a short transition period, in 2020 the API funcionality is avaliable, however no new subscriptions are accepted. Therefore past 2021 it won't be possible any more to aquire any dataset via the [Darksky API](https://darksky.net/dev).

The Budapest Waether Data for 2000-2020 is available under [BP_years](https://github.com/xngst/Budapest_idojaras_2000-2020/tree/main/BP_years)


### Units used in dataset
Data is in SI units as follows:

* summary: Any summaries containing temperature or snow accumulation units will have their values in degrees Celsius or in centimeters (respectively).
* nearestStormDistance: Kilometers.
* precipIntensity: Millimeters per hour.
* precipIntensityMax: Millimeters per hour.
* temperature: Degrees Celsius.
* temperatureMin: Degrees Celsius.
* temperatureMax: Degrees Celsius.
* apparentTemperature: Degrees Celsius.
* dewPoint: Degrees Celsius.
* windSpeed: Meters per second.
* windGust: Meters per second.
* pressure: Hectopascals.
* visibility: Kilometers.

##### Are historical reports based on observational data?  
Usually, but we sometimes fill in data from other sources if no observations are available.  

##### Why do historical reports sometimes change from the last time I requested them?  
Several of our data sources aren’t real-time, and flow into our system after the fact. As a result, our historical data may continue changing for up to two weeks after a time has occurred. (In most cases, the changes are very minor!)  

##### Why are weather conditions sometimes missing from historical responses?  
We omit weather data that we do not have. This may be because there aren't any weather stations near you, or the weather stations that are near you are missing sensors for the kind of weather that you care about, or the weather stations that are near you have those sensors but are producing suspect data (in which case we ignore it).  

##### Why isn't precipProbability always 0 or 1 for historical responses?  
We don't have perfect historical data—weather stations don't cover every square inch of the planet!—and so these probabilities reflect our uncertainty about what happened.  

##### Can I get your previous forecasts instead of weather station observations?  
Unfortunately, we do not have the storage capacity to store previous forecasts. Sorry!  

