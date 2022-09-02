# Ethiopia_CHIRPS

## I. Precipitation Data

First we will obtain the precipitation data for Ethiopia, from the CHIRPS satellite using GEE (Google Earty Engine) API. For this we need to run the python code "Precipitation_2022" which downloads the precipitation data for Ethiopia for the period between January and July of 2022. We will get a csv. file that contains min, max and mean by month and year. Then we run the python code "Precipitation_2012_2021" that consists of the same code as "Precipitation_2022" but calculates min, max and mean precipitation for the period between 2012 and 2021, produces a csv file (much like the one produced by  "Precipitation_2012_2021") and appends both csv files so we have the whole period between 1/1/2012 and 31/07/2022. I based this code on [GitHub](https://github.com/mnvlucian/Google-Earth-Engine-CHIRPS-Statistics/blob/main/CHIRPS_Statistics.ipynb), [Google Earth Engine](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api) and this [Blog](https://bikeshbade.com.np/tutorials/Detail/?title=Chirps%20Precipitation%20to%20Excel%20-%20GEE%20and%20Pandas&code=14).

## II. SPI (Standard Precipitation Index)

Then I calculate the Standard Precipitation Index using `standard_precip.spi` package on Python. For this I use the precipiation data obtained from CHIRPS, as explained above. I based this code on [Code](https://github.com/e-baumer/standard_precip/blob/master/examples/example_use.ipynb).

