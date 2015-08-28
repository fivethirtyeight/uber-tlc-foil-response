### Uber TLC FOIL Response

This directory contains data on over 4.5 million Uber pickups in New York City from April to September 2014. Trip-level data on 10 other for-hire vehicle (FHV) companies, as well as aggregate analysis, is also included. All the files are as they were received on August 3, 2015. 

FiveThirtyEight obtained the data from the [NYC Taxi & Limousine Commission (TLC)](http://www.nyc.gov/html/tlc/html/home/home.shtml) by submitting a Freedom of Information Law request. The TLC's correspondence with FiveThirtyEight is included in the file `TLC_letter.pdf`. TLC records requests can be made [here](http://www.nyc.gov/html/tlc/html/passenger/records.shtml).

This data was used for two FiveThirtyEight stories: [Uber Is Serving New York’s Outer Boroughs More Than Taxis Are](http://fivethirtyeight.com/features/uber-is-serving-new-yorks-outer-boroughs-more-than-taxis-are/) and [Public Transit Should Be Uber’s New Best Friend](http://fivethirtyeight.com/features/public-transit-should-be-ubers-new-best-friend/).

In the folder `uber-trip-data`, there are six files of raw data on Uber pickups in New York City from April 2014 through September 2014. The files are separated by month and each has the following columns:

Header | Definition
---|---------
`Date/Time` | The date and time of the Uber pickup
`Lat` | The latitude of the Uber pickup
`Lon` | The longitude of the Uber pickup
`Base` | The [TLC base company](http://www.nyc.gov/html/tlc/html/industry/base_and_business.shtml) code affiliated with the Uber pickup

The `Base` codes are for the following companies:

Base Code | Base Name
---|---------
B02512 | Unter
B02598 | Hinter
B02617 | Weiter
B02682 | Schmecken
B02764 | Danach-NY

In the folder `other-FHV-data`, there are 10 files of raw data on pickups from 10 for-hire vehicle (FHV) companies. The trip information varies by company, but can include day of trip, time of trip, pick-up location, driver's for-hire license number, and vehicle's for-hire license number.

The file `Aggregate_FHV_Data.xlsx`, which contains aggregate analysis on taxi and FHV trips, came directly from the TLC.

The file `Uber-Jan-Feb-FOIL.csv` contains aggregated daily Uber trip statistics in January and February 2015.
