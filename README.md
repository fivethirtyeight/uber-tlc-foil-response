### Uber TLC FOIL Response

This directory contains data on over 4.5 million Uber pickups in New York City from April to September 2014, and 14.3 million more Uber pickups from January to June 2015. Trip-level data on 10 other for-hire vehicle (FHV) companies, as well as aggregated data for 329 FHV companies, is also included. All the files are as they were received on August 3, Sept. 15 and Sept. 22, 2015. 

FiveThirtyEight obtained the data from the [NYC Taxi & Limousine Commission (TLC)](http://www.nyc.gov/html/tlc/html/home/home.shtml) by submitting a Freedom of Information Law request on July 20, 2015. The TLC has sent us the data in batches as it continues to review trip data Uber and other HFV companies have submitted to it. The TLC's correspondence with FiveThirtyEight is included in the files `TLC_letter.pdf`, `TLC_letter2.pdf` and `TLC_letter3.pdf`. TLC records requests can be made [here](http://www.nyc.gov/html/tlc/html/passenger/records.shtml).

This data was used for four FiveThirtyEight stories: [Uber Is Serving New York’s Outer Boroughs More Than Taxis Are](http://fivethirtyeight.com/features/uber-is-serving-new-yorks-outer-boroughs-more-than-taxis-are/), [Public Transit Should Be Uber’s New Best Friend](http://fivethirtyeight.com/features/public-transit-should-be-ubers-new-best-friend/), [Uber Is Taking Millions Of Manhattan Rides Away From Taxis](http://fivethirtyeight.com/features/uber-is-taking-millions-of-manhattan-rides-away-from-taxis/), and [Is Uber Making NYC Rush-Hour Traffic Worse?](http://fivethirtyeight.com/features/is-uber-making-nyc-rush-hour-traffic-worse/).

In the folder `uber-trip-data`, there are six files of raw data on Uber pickups in New York City from April to September 2014. The files are separated by month and each has the following columns:

Header | Definition
---|---------
`Date/Time` | The date and time of the Uber pickup
`Lat` | The latitude of the Uber pickup
`Lon` | The longitude of the Uber pickup
`Base` | The [TLC base company](http://www.nyc.gov/html/tlc/html/industry/base_and_business.shtml) code affiliated with the Uber pickup

Also in the folder is the file `uber-raw-data-janjune-15.csv.zip` The unzipped file has the following columns:

Header | Definition
---|---------
`Dispatching_base_num` | The [TLC base company](http://www.nyc.gov/html/tlc/html/industry/base_and_business.shtml) code of the base that dispatched the Uber
`Pickup_date` | The date and time of the Uber pickup
`Affiliated_base_num` | The [TLC base company](http://www.nyc.gov/html/tlc/html/industry/base_and_business.shtml) code affiliated with the Uber pickup
`locationID` | The pickup location ID affiliated with the Uber pickup

The `Base` codes are for the following Uber bases:

Base Code | Base Name
---|---------
B02512 | Unter
B02598 | Hinter
B02617 | Weiter
B02682 | Schmecken
B02764 | Danach-NY
B02765 | Grun
B02835 | Dreist
B02836 | Drinnen

The file `taxi-zone-lookup.csv` shows the taxi `Zone` and `Borough` for each `locationID`

In the folder `other-FHV-data`, there are 10 files of raw data on pickups from 10 for-hire vehicle (FHV) companies. The trip information varies by company, but can include day of trip, time of trip, pickup location, driver's for-hire license number, and vehicle's for-hire license number.

There is also a file `other-FHV-data-jan-aug-2015.csv` containing daily pickup data for 329 FHV companies from January 2015 through August 2015.

The file `Aggregate_FHV_Data.xlsx`, which contains aggregate analysis on taxi and FHV trips, came directly from the TLC.

The file `Uber-Jan-Feb-FOIL.csv` contains aggregated daily Uber trip statistics in January and February 2015.
