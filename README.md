# Mapping_Earthquakes
Mapping Earthquakes with JavaScript and APIs

## Overview 
***Background***
To tell a story with data through interactive maps, this module goes over using Leaflet.js Application Programming Interface (API) to create a map with GeoJSON earthquake data. By the end of the module and challenge, we are able to: 

- Create a branch from the main branch on GitHub. Add, commit, push and merge data to a GitHub branch.
- Retrieve data from a GeoJSON file.
- Make API requests to a server to host geographical maps.
- Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
- Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
- Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
- Render maps on a local server.


***Purpose***
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Resources 
- Original Data Source: [Earthquake Data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) and [Tectonic Plate Data](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json).
- Software: JavaScript, D3.js, Leaflet.js, Mapbox 


## Results
To create a map showing the magnitudes of earthquakes in the last seven days, we used the GeoJSON earthquake data from the USGS website ([Earthquake Data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)) to retrieve the geographical information from earthquakes over the last seven days. In addition to adding earthquakes on our map, we added tectonic plates and major earthquake (magnitude of 4.5 or greater) layers to our geographical map. In addition to these layers, we included (3) different backgrounds as tile layers (Street, Satellite, and Dark Mode). 

Click [HERE]() to see the deployed interactive website demonstrating our findings. 


## Summary 
To create these interactive maps of earthquakes over the past seven days, we used Javascript and the D3.js library to retrieve the earthquake data (coordinates, magnitudes) and a github file for our tectonic plate data. Next, we used the Leaflet library to create interactivity with the earthquake data. Using the toggle button on the top right hand corner, viewers can switch between background layouts (Street, Satellite and Dark Mode) and also turn off/on the different layers (Earthquakes, Tectonic Plates, and Major Earthquakes). 

From our interactive earthquake maps, We can see that most of the major earthquakes are near or ontop of the tectonic plates. 
