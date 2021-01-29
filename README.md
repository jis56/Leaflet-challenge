## Leaflet-challenge

# Level 1: Basic Visualization

A visualization was created based on all earthquake data from the past 7 days from USGS GeoJSON Feed page (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). A map was created using Leaflet that plots all the earthquakes from the data set based on longitude and latitude while also including the following:

  - data markers that reflect magnitude of the earthquake by size and depth of the earthquake by color
  - popups that provide additional information about the earthquake when marker is clicked
  - legend that provides context for map data
  
# Level 2: More Data

A second visualization was created to illustrate the relationship between tectonic plates and seismic activity. Data on tectonic plates was pulled from https://github.com/fraxen/tectonicplates. In this step, the following was added to our original map:
  
  - a second data set was plotted
  -  additional base maps were added that separate the 2 data sets into overlays that can be turned on and off       independently 
  - layer control was added to map
