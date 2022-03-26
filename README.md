# Mapping Earthquakes

![Screenshot of webapp](earthquake_challenge/earthquake_challenge.png)

## Overview

This web app is a visualization of USGS earthquake data for the past 7 days. Users can choose to view all earthquakes, major earthquakes, and the main tectonic plates. There are three base map tiles to choose from.

## How does it work?

Javascript is used to perform most of the functionality in this app. Leaflet.js provides the visualization and d3.js allows us to connect to the USGS geoJSON data. We use the Mapbox API to pull the map tiles for our base maps. 

### Leaflet.js

We use leaflet.js because it is built for easily using geoJSON data. Since geoJSON conforms to set standards, we don't need to do any transformation of the data, and can use it right away. We use leaflet's functions for changing markers to visualize the data we are showing, and to improve visibility. 

## Future Changes

Given the large difference in color for the base maps it was difficult to find marker colors that complemented each other and were still easy to see on the background. It would be easier to change the marker overlay colors based on what base map tile is chosen, especially for the lines denoting the tectonic plates. Additionally a legend for the colors of the major earthquakes would be helpful.
