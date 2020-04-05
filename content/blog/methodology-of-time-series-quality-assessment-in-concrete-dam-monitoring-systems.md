---
path: timeseries-quality-pshpp
date: 2020-04-05T09:56:30.972Z
title: >-
  Methodology of time series quality assessment in concrete dam monitoring
  systems
description: Modelling of water losses in hydraulic tunnels.
---
Thermal-seepage-stress analysis represent an essential part of dam health monitoring. The average large dam in Europe is about 50 years old, which puts dam operators in urgent need for upgrading and improvement of dam monitoring and decision-support systems. 

Reliability of the analysis is primarily dependent on quality of measured data, organized and stored in form of time series. 

![Water level change in surge tank during the measurement of total water losses](/assets/tsmeasurements.png "Water level change in surge tank during the measurement of total water losses")

Here i will present a methodology for the assessment of monitored data related to thermal, seepage and deformation processes. The methodology is based on the consensus of several state of the art statistical and ML outlier detection methods, supplemented by hybrid and original methods. 

![Developed methodology for modelling of total water losses in hydraulic tunnels: (a) Schematic overview; and, (b) Stepwise regression modelling method.](/assets/metodologijaflow.jpg "Developed methodology for modelling of total water losses in hydraulic tunnels: (a) Schematic overview; and, (b) Stepwise regression modelling method.")

This methodology was applied by building a MLR model of water losses with greater accuracy and reliability, compared to previously developed models of water losses. The case study was carried out for the hydraulic tunnel at PSHPP “Bajina Basta”, located on Drina river, in the Republic of Serbia.

![Map of Serbia showing the river Drina and the position of the PSHPP Bajina Basta.](/assets/lokacija.jpg "Map of Serbia showing the river Drina and the position of the PSHPP Bajina Basta.")

A novel _Superimposed Multiple Linear Regression_ model has shown some advantages over traditional regressions, especially in case of time series with frequent and rapid changes of pattern. Due to different nature of dam monitoring time series, variants of the methodology are proposed for time series with strong seasonal behavior and those strongly dependent on other measurements, such as water level. The proposed approach was validated using case study of large arc dam located in southeastern Europe, where time series related to thermal and seepage processes were assessed.
