# Visualizing Data with Leaflet

## Background

The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

## The Task

### Basic Visualization

Your first task is to visualize an earthquake data set.

1. **Get data set**

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visited the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and chose a All Earthquakes from the Past 30 Days, from which I was given a JSON representation of that data. I used the URL of the JSON to pull in the data for the visualization.

2. **Import & Visualize the Data**

   Created a map using Leaflet that plots all of the earthquakes from the data set based on longitude and latitude.

   * The data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

   * Included popups provide additional information about the earthquake when a marker is clicked.

   * The legend provides context for the map data.

