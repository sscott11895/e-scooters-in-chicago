# From Point A to Point B: E-Scooters as a Mode of Transportation in Chicago
When I moved to Chicago in 2021, I was interested in the city's green initiatives. 
One popular, and at times controversial, initiative was the introduction of e-scooters
in various neighborhoods around Chicago. While this new mode of transportation offers 
commuters and tourists an alternative to gas-powered vehicles, concerns around sidewalk
clutter are often sources of debate. 


Chicago piloted an E-Scooter program in 2020 to test how city residents would
respond to this new mode of transportation. The city’s full report can be found [here](https://www.chicago.gov/content/dam/city/depts/cdot/Misc/EScooters/2021/2020%20Chicago%20E-scooter%20Evaluation%20-%20Final.pdf).

The goal of my analysis is to look at the origin and end points of scooter rides.
Where were these novel wheels popular and where did they sit growing dust and 
rust on the sidewalk? I am using the raw data provided on the City of Chicago website, 
which can be found [here](https://data.cityofchicago.org/Transportation/E-Scooter-Trips-2020/3rse-fbp6).


# Contents

The R Markdown is included in this repo with various plots and maps that supported 
my analysis (see here for full report). During the data manipulation and processing phase, I used geolocation data 
to review trip duration, trip distance, origin communities, and destination communities.  

I then used a brief time-series analysis to see the number of trips taken over time. 
From mid-August to early September, we can see that residents quickly learned 
of the program and began utilizing the scooters. The number of rides generally 
decreases over time which is congruent with the expected drop in temperatures as 
the weather changes throughout the fall.

Finally, I used maps to visualize communities where e-scooters were very popular based on 
ridership. After looking at this data, it is clear that scooters were well utilized
in neighborhoods in the north of Chicago. While more data is needed to understand why 
people in southern neighborhoods might not choose to travel by bike, one conjecture we 
could make is that people in northern Chicago might live and work within a two block radius. 
In contrast, people in southern Chicago might travel farther to get to work and therefore 
traveling by scooter is a less attractive option.

![E-Scooter Origin Communities](https://github.com/sscott11895/e-scooters-in-chicago/blob/main/e_scooters_ride_start_loc.png)

Moving forward, Chicago should capitalize on the demand in the neighborhoods of Lake View, Lincoln Park, and 
West Town and put the majority of e-scooters/e-scooter charging stations there. 
Simultaneously, they should survey neighborhoods in the Southside to determine future demand.