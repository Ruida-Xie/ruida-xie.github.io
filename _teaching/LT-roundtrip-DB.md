---
title: "Low-thrust Roundtrip trajectories"
collection: teaching
type: ".MAT format"
permalink: /teaching/2014-spring-teaching-2
venue: "SIZE - 15 GB"
date: 2021-10-01
---

This database stores low-thrust roundtrip missions to NEAs. The generation of this database used our advanced deep learning low-thrust transfer cost approximation technique, which replace the conventional optimization process. The estimation of low thrust transfer cost is as fast as solving a Lambert problem. The search process is based on grid search.

## Database Summary

| Item                             | Description                                                                           |
|----------------------------------|---------------------------------------------------------------------------------------|
| Recorded asteroid number         | 24,149 NEAs were searched, 1,684 NEAs (7%) are confirmed to be round trip accessible  |
| Number of roundtrip trajectories | 695,511,547                                                                           |
| File Format                      | -                                                                                     |
| File Size                        | -                                                                                     |
| Precision                        | double-precision floating-point                                                       |
| Coloumns                         |                                                                                       |

## Statistics
![Statistics of the database](/images/DB2-stats.png "Statistics")

## Methodology
### DNN – Classifier
* Input: Classifier features, such as initial mass, time of flight, etc.
* Output: Two classes, representing feasible and infeasible Transfers
* Prediction Accuracy: ~ 98%
### DNN - Regressor
* Input: Regressor features, such as initial mass, time of flight, etc.
* Output: Single value of the predicted spacecraft final mass
* Prediction Mean Relative Error: < 1%

![DB2-architecture](/images/DB2-architecture.png "DB2-architecture")
![Search Scheme](/images/DB2 search-scheme.png "Search Scheme")

## Download Link
The link will be released later

