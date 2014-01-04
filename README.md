Made 12/30/13.

Uses Wunderground API for 10 day hourly weather and some custom filters to find out what times are best for cycling and makes a pretty table.

Usage:
```
hourlyWeather(tableDiv, zipCode, sleepTime)
```

| Parameter | description 						 						|
| tableDiv  | jQuery div for <table> DOM element 						|
| zipCode   | zipCode for where you want weather from 					|
| sleepTime | (optional) length 2 array of start/end hours you sleep 	|