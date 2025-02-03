# leaflet-challenge
# Earthquake Visualization
## Deploy here: https://vmendez2000.github.io/leaflet-challenge/
### This project visualizes recent earthquake data from the USGS Earthquake feed using Leaflet for the map and D3.js for data visualization. The map displays earthquake markers with size and color reflecting the earthquake's magnitude and depth, respectively. A legend is provided to explain the color scale for earthquake depth.

## Project Overview
* The map is built using the Leaflet library, displaying earthquake data sourced from the USGS GeoJSON API.
* Earthquake markers are styled based on the earthquake's magnitude and depth.
* A popup is shown when a marker is clicked, displaying the earthquake's location, magnitude, and depth.
* A legend is added to the map to indicate depth-based color coding.
## Features
* Interactive Map: Displays earthquake markers that are clickable for more information.
* Marker Sizing: The size of each marker corresponds to the magnitude of the earthquake.
* Depth Coloring: Markers are color-coded based on the earthquake's depth (e.g., deep earthquakes are red, shallow ones are green).
* Legend: A color-coded legend explains the depth categories.
## Installation and Setup
### 1. Clone or download the repository.
### 2. Open index.html in your browser to view the map and the visualization.
## File Structure
* index.html: The main HTML file that sets up the map and loads the earthquake data.
* static/js/logic.js: The JavaScript file responsible for handling the data fetch, processing, and map interactions.
* static/css/style.css: The custom styles for the map and layout.
## Code Source
* Leaflet Tile Layer: Leaflet
* D3.js for Data Fetching and Visualization: D3.js
* USGS Earthquake Data: The earthquake data is sourced from the USGS Earthquake API: USGS Earthquake Feed
## Acknowledgments
* The base map layer is provided by OpenStreetMap.
* Data is retrieved from USGS Earthquake Feed.
* Legend colors and marker sizing logic are adapted from various tutorials on Leaflet and D3.js.
## Resources
### ChatGBT was used to help execute the project.
