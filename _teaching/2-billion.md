---
title: "2 Billion Impulsive Round-trip Trajectories"
collection: teaching
type: ".MAT format"
permalink: /teaching/2014-spring-teaching-1
venue: "SIZE - 8GB"
date: 2020-01-01
---

This database stores nearly two billion impulsive round-trip trajectories to near Earth asteroids.  This database enables numerical approach for mission analysis.
The visualization of this database can be found on http://www.traplan.xyz/data.html. You may find an insecure icon on your chrome browser, this because the website is under development and I haven’t purchase a https certificate. Please simply ignore that. Please allow some minutes for the database to load.

## Assumptions and Caveats
* Data source: HORIZONS
* Searching period: Between 2030-01-01 and 2065-01-01
* Searching step : 15-days step for departure date and stay time, 10-days step for outbound and inbound flight time
* Launch energy Earth departure C3 less than or equal to 80 km2/sec2
* Mission duration less than or equal to 6 years
* Outbound/inbound ToF less than or equal to 6 years
* Departure orbit: 400km circular Earth Parking Orbit
* Returning orbit: high elliptical orbit with perigee altitude 200km and apogee altitude 200,000km(eccentricity 0.998).
* Delta-V of round trips less than or equal to 12 km/s
* The total delta-V includes the Earth departure maneuver from a 400 km altitude circular parking orbit, the maneuver to match the NEA's velocity at arrival, the maneuver to depart the NEA and the maneuver to capture the elliptical orbit during Earth return.
* No mid course maneuvers, gravity assists or continuous thrust options
