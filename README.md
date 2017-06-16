# Visualization of world map and airport location by D3js
This repository includes the materials reference and demo for visualizing the world map (include countries information) and airport locations by D3js.
## [Demo Link](https://bill9800.github.io/World-Map-Airport-d3js/)
- click on the map to zoom in and zoom out.
- click on the country you like to get further information about it.
- The red dots are represented as the location of the airport, and it contains wiki link to know more information about it. 
## Preparation
1. Get world map information from [**Natural Earth**](http://www.naturalearthdata.com/). 
2. Get airport location information also from Natural Earth.
3. Because the map file is not available to be used by D3js, transfer the file to topojason on [**Mapshaper**](mapshaper.org).
4. Use web crawler to get more information about the airport. I wrote a python web crawler to complete this task.
