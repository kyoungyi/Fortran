# NASS Crop Data

Long format – unbalanced datasets (have missing values at some time observations for some of the counties)

*Process
1. Combine PRISM weather data with shapefile in an order of shapefile’s order
2. Combine the outcome of (1) with NASS corn in line with correct state and county
3. Unavailable datapoints => Nan
  
  1)NASS Corn
  State and County level
  •State
  and county name & ID
  •Corn
  (rainfed+irrigated)
  yield (Bu/ac)

  •Harvested
  Corn area (ac)
  •Lon
  and lat

  •Total
  counties: 3108
  üValid counties: 2831
  üInvalid counties: 277

 2)Shapefile
  State and County Level
  •State
  and county name & ID
  •Lon
  and lat
  (central points)
  
  •Total
  counties: 3220
  üValid counties: 3220
  üInvalid counties:0
  
  3) PRISM Weather
  State and County level

  •Growing
  season (Mar – Aug) (Wolfram and Roberts, 2009)
  •Yearly gs mean temp (Celcius/yr)
  •Yearlygs accumulated precip (mm/yr)
   ** If any month is unavailable at a county
  for the calculation of temp and precip, it becomes Nan.

  •Total
  counties: 3220
  üValid counties: 3106
  üInvalid counties: 114 (Hawaii, Alaska,
  Puerto Rico, etc.) 
  
----------------------------------------------------
Total counties: 3222
Counties in common: 2829
Counties only in NASS corn: 2 (Shannon and Bedford)
Counties only in PRISM: 391


  
 

 

  
 

