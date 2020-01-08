# 06-Python-APIs-Homework

The following analysis used weather information from Open Weather Map via the Open Weather map API to query and record maximum temperature, humidity, cloudiness, and wind speed for 574 world cities on January 5th, 2020. The python library citipy was used to retrieve the closest city near a pair of randomly generated latitude and longitude coordinates. The results of the analysis were plotted to visualize observable trends.

Observed Trend One:
As expected, the highest temperatures observed in the sample of cities occurred in cities located between the latitudes 20 degrees north and south of the equator. As it is the middle of winter in the Northern Hemisphere, temperatures at equal distance from the equator are lower on average in positive latitudes than in negative latitudes.

Observed Trend Two:
There does not seem to be trends of note in humidity, cloudiness, or wind speed. However, the majority of cities sampled experienced humidity over 40% and wind speeds less than 30 mph. Wind speed tended to be higher as city locations were farther away from the equator.

Observed Trend Two:
Although the sample is representative of many different locations around the world, information for only one day was used. A bigger sample of data over a much longer period of time would be needed to provide more insight into world weather trends.
