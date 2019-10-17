# GIS Intern - Technical tasks

Thanks for applying to work at FATMAP. We have developed these small tasks for you to work on in your own time, so that 
we can see how you approach tasks and as a discussion point going forwards.

Take all the time you need to develop this task - and don't worry if it is not complete, we prefer to see quality over quantity. 

Please use python 2.7 or higher to execute the first task.

## The tasks

### 1. Import OSM points and export them to a geojson file
Write a python script to import at least 50 points from Open Street Map. Those points must represent 50 alpine huts 
located in the Alps (Europe ) and/or the Rocky Mountains (USA), and should contain all the properties present in Open Street Maps. 
Once imported, make the python script to export a geojson file with all the points geometries and properties.

__Task tip:__ as an option, you can use the [Python Overpass API](https://python-overpy.readthedocs.io/en/latest/) to import the OSM points.

__Bonus:__ generate a [Leaflet](https://leafletjs.com) map and place those points with points markers.

### 2. Split a raster image with GDAL
Imagine you have downloaded a remote sensing scene captured by the Sentinel satellite, for example the file 
`L1C_T60GTA_A022148_20190918T221600.TIF`. 
We ask you to generate a terminal command using the [GDAL](https://gdal.org) library to split that image in four parts with exactly the same extension.

__Bonus:__ Find out what is the default projection for the Sentinel imagery data bank and generate another terminal 
command to reproject the image to EPSG:3857, involving some sort of compression and cubic resampling.


For both tasks, document all your steps as much as you can so we can understand how you have approached the tasks.

Commit the files for both tasks to a public Git repository or send them back to us via email.