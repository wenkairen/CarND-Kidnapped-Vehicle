# CarND-Kidnapped-Vehicle
self-driving second term 

# Localization Project Introduction
In this project you will implement a 2 dimensional particle filter in C++. Your particle filter will be given a map and some initial localization information (analogous to what a GPS would provide). At each time step your filter will also get observation and control data.

# Code description:
The code includes:
1. main.cpp : calls for the partical fileter and acces the data flow 
2. particle_filter.cpp: the acutal implement function, with initialize, predict, updateweights, and resample.
3. particle_filter.h
4. helper_functions.h: some useful funcitons used for calculation
5. map.h: the information of the map data

# The simulated result:
Based on the map and sensor data, the filter has successful passed the test within time:

![p_result.png](https://github.com/wenkairen/CarND-Kidnapped-Vehicle/blob/master/p_result.PNG)


