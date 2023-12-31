# leaflet-challenge
[`GitHub Page`](https://lakigit.github.io/leaflet-challenge/)
# Bachground of the Project
The United States Geological Survey, or USGS for short, provides scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and valuable information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualise their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, developing a way to visualise USGS data will allow them to better educate the public and other government organisations (and hopefully secure more funding) on issues facing our planet.

The task is to visualise an earthquake dataset. Complete the following steps:
1. Get dataset. To do so, follow these steps:
   - The USGS provides earthquake data in several different formats, updated every 5 minutes. Visit the [`USGS GeoJSON Feed`](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). page and choose a dataset to visualise.
2. Import and visualise the data by doing the following:
   - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
     - Data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by colour. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in colour.
   - Include popups that provide additional information about the earthquake when its associated marker is clicked.
   - Create a legend that will provide context for the map data.
   - Visualisation should look something like the preceding map.
