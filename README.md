# Leaflet-challenge
# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

Overview
Part 1: Create the Earthquake Visualization

Part 2: Gather and Plot More Data (Optional)

Part 1: Create the Earthquake Visualization
Gather the earthquake data:

The USGS provides earthquake data in a number of different formats, updated every five minutes. USGS GeoJSON Feed

The dataset "All Earthquakes from the Past 7 Days") gave a JSON representation of that data. The URL of this JSON was used to pull in the data for the visualization.

Import and visualize the data by doing the following:

Leaflet was used to create a map that plots all the earthquakes from the dataset based on their longitude and latitude.

The data markers reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes appear larger, and earthquakes with greater depth appear darker in color.
Popups are included that provide the following information about the earthquake when its associated marker is clicked: location, magnitude, and depth.

A legend is included that will provide context for the map data.
