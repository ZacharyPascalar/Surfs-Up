# Surfs-Up
## Overview 
Hoping to start a Surf and Ice Cream shop in Oahu, Hawaii, a potential investor W. Avy is looking for more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, to determine if the surf and ice cream shop business is sustainable year-round.

## Results: 
Using jupyter notebooks, we're able to provide statistical information about the temperatures in Oahu for the months of both June and December.

#### June Temperature Statistics

![June Temperature Statistics](/June_Temps.png)

#### December Temperature Statistics

![December Temperature Statistics](/Dec_Temps.png)

Hawaii is known for its consistent climate throughout the year, and the above statistics show there is only slight variation from June to December regarding temperature.
- The average temperature in June is 74.9 degrees, whereas in December it is 71.0. Though it is mildly colder in December, it is still reasonable for outdoor recreation (surfing) and dining (ice cream). Even moreso if they're tourists from a colder area.
- Looking and the minimum temperature for these months, we do see that it can reach temperatures in both months that are likely cooler than ideal for a surf and ice cream shop (64 degrees in June and 56 degrees in December). However, we can see from the above data that only a quarter of the temps measured were 69 degrees or lower in December, and in June this lowest quarter were between 64 and 73 degrees.
- The maximum temperatures for both months are consistent with the rest of the year and only a couple of degrees different (June max temp is 85 degrees, December max temp is 83 degrees)

## Summary:
The results above show that Oahu has ideal temperatures in June and December for a surf and ice cream shop. However, there are other factors at play which could affect the success of the business.  

Additional queries need to be reviewed to look at precipitation for these two months. Ideally, we would also have data for wind speed, but that isn't provided in the database we used for the temperature query.

Using the data we have, it would be worthwhile to look at temperature and precipitation grouped by time of day. If we assume the majority of our surfing business would be during daylight, and ice cream sales would likely be in afternoon, stratifying data by time of day would be useful (and possible using dataframes). 
