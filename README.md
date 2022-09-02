# Ethiopia_CHIRPS

## I. Precipitation Data

First we will obtain the precipitation data for Ethiopia, from the CHIRPS satellite using GEE (Google Earty Engine) API. For this we need to run the python code "Precipitation_2022" which downloads the precipitation data for Ethiopia for the period between January and July of 2022. We will get a csv. file that contains min, max and mean by month and year. Then we run the python code "Precipitation_2012_2021" that consists of the same code as "Precipitation_2022" but calculates min, max and mean precipitation for the period between 2012 and 2021, produces a csv file (much like the one produced by  "Precipitation_2012_2021") and appends both csv files so we have the whole period between 1/1/2012 and 31/07/2022. 

## II. SPI (Standard Precipitation Index)

Then I calculate 
