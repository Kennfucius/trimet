Weather Stations for KPDX and KHIO

Data downloaded from NOAA's ISD integrated Surface Database of
automated stations.  From here:
https://www.ncdc.noaa.gov/isd/data-access
ftp://ftp.ncdc.noaa.gov/pub/data/noaa/isd-lite/

Need to know USAF and WBAN codes to identify stations.
Can find the stations in isd-history.txt.
If you don't know the ICAO airport codes, you can use the list from
here:https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat

726980-24229 is KPDX (Portland International)
726986-94261 is KHIO (Hillsboro)

These are the two big airports I'm aware of in the Portland area.

Each file is one year of data for a given station.

Column Info (taken from isd-lite-format.txt):
1: Year
2: Month
3: Day
4: Hour 
5: Temperature (x10) in celcius
6: Dew point temperature (x10) in celcius
7: Sea level pressure (x10 in hectopascals)
8: Wind direction (degrees from north)
9: Wind speed 
10: Cloud Coverage (categorical)
11: Precipitation for One Hour (x10, in mm)
12: Precipitation total for Six hours (x10 in mm)
