Az elemzés alapjául szolgáló tényadatok a [darksky.net](https://darksky.net/)-oldaltól származnak és a darksky [API](https://darksky.net/dev)-ján keresztül lettek kinyerve.  

> (Az Apple Inc. 2020-ban [felvásárolta](https://edition.cnn.com/2020/03/31/tech/apple-dark-sky/index.html) az oldalt valamint a hozzá tartozó összes alkalmazást, majd nem sokkal később bejelentették hogy 2021-től kezdődően teljesen megszűntetik az API szolgáltatást, illetve [leállítják](https://blog.darksky.net/) az android és iOS applikációkat is.)

A Budapestre vonatkozó csvformátumú éves bontású adatokat a [BP_years](https://github.com/xngst/Budapest_idojaras_2000-2020/tree/main/BP_years) mappában lehet majd megtalálni.  

Az adatról:

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

