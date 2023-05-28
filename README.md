# Leftbank-Rightbank-identification
Identification of left and right bank from bankline polygon shapefile

The script needs module from geopandas and shapely python libraries
The script take input bankline polygon shapefile as geopandas geodataframe
The script also take input as the lower and upper limit in termos of y coordinates to clip the shapefile
The upper and lower limit y coordinate must be in the coordinate system of the bankline spatial reference system
The script output the left and right bankline as seperate geodataframe in input bankline coordinate system
