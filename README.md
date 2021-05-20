# Appliances-Energy-Prediction

This project deals with predicting appliances energy consumption of a particular household in Belgium based on the temperature and humidity levels of different rooms in the building and the weather reports in the area over a period of 4.5 months.

The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non-predictive attributes (parameters).

### Dataset Link

* [Appliance Energy Data](http://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction)

### Dataset Information

* Number of instances: 19,735
* Number of attributes: 29

### Attribute Information

1. date: year-month-day hour:minute:second 
2. T1: Temperature in kitchen area, in Celsius  
3. RH_1: Humidity in kitchen area, in %  
4. T2: Temperature in living room area, in Celsius  
5. RH_2: Humidity in living room area, in %  
6. T3: Temperature in laundry room area  
7. RH_3: Humidity in laundry room area, in %  
8. T4: Temperature in office room, in Celsius  
9. RH_4: Humidity in office room, in %  
10. T5: Temperature in bathroom, in Celsius  
11. RH_5: Humidity in bathroom, in %  
12. T6: Temperature outside the building (north side), in Celsius  
13. RH_6: Humidity outside the building (north side), in %  
14. T7: Temperature in ironing room, in Celsius  
15. RH_7: Humidity in ironing room, in %  
16. T8: Temperature in teenager room 2, in Celsius  
17. RH_8: Humidity in teenager room 2, in %  
18. T9: Temperature in parents’ room, in Celsius  
19. RH_9: Humidity in parents’ room, in %  
20. T_out: Temperature outside (from Chievres weather station), in Celsius  
21. Pressure: (from Chievres weather station), in mm Hg  
22. RH_out: Humidity outside (from Chievres weather station), in %  
23. Wind speed: (from Chievres weather station), in m/s  
24. Visibility: (from Chievres weather station), in km  
25. T_dewpoint: (from Chievres weather station), Â°C  
26. rv1: Random variable 1, non-dimensional 
27. rv2:  Random variable 2, non-dimensional 
28. Lights: energy use of light fixtures in the house in Wh  
29. **Appliances: energy use in Wh  (Target Variable)**

Where indicated, hourly data (then interpolated) from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis, rp5.ru. Permission was obtained from Reliable Prognosis for the distribution of the 4.5 months of weather data.
