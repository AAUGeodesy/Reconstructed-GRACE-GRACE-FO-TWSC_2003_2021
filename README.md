To fill the gap months of GRACE (2003-2017) and GRACE-FO (2018-2021)and the extended 1 year gap between the two missions,
we applied the approach of https://www.mdpi.com/2072-4292/12/10/1639 , who applied an iterative decomposition approach to fill the existing gaps. 
This reconstruction approach uses the Terrestrial Water Storage Changes (TWSC) derived from the temporal gravity field products of the ESA's Swarm mission as initial values for the missing fields. 
Then, the Independent Component Analysis is applied to update these initial values using the statistics existing in the time series of GRACE, GRACE-FO, and Swarm TWSC fields.
FilledGap_GRACE-FO-TWSC50km.mat is a MATLAB file containing:

     TWSC_50km.mat : a 2D matrix, where each column is the time series of TWSC for 58984 spatial grid points  over the continental reion with 0.5 degree (50km) resolution.
     
     Time_TWSC.mat :  Time vector.
     
     Lat.mat : the vectore of latitude for global 50km grid of TWSC.
     
     Lon.mat : the vectore of longitude for global 50km grid of TWSC.
     
     Landmask_50km : vector of continental mask.
