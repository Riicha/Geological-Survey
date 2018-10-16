# Geological-Survey
This project is about providing scientific data on Natural Hazards, the Health of our Ecosystems and Environment; and the impacts of climate and land-use change. It is based on the new methods developed by scientists. They serve as tools to supply timely, relevant, and useful information about the Earth and its processes.

## Background

![1-Logo](Images/1-Logo.png)

The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards &  health of our ecosystems.

A new set of tools is built in this project that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Basic Visualization Done :-

![2-BasicMap](Images/2-BasicMap.png)


   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When we click on a data set, for example 'All Earthquakes from the Past 7 Days', we will be given a JSON representation of that data. we used the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Created a map using Leaflet that plots all of the Earthquakes from our Dataset based on their Longitude and Latitude.

   -- The data markers should reflect the magnitude of the Earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

   -- Included popups that provide additional information about the Earthquake when a marker is clicked.

   -- Created a legend that will provide context for our Map Data.

   -- our visualization should look something like the map in the above image.

- - -

![5-Advanced](Images/5-Advanced.png)

If the USGS want  to plot a second data set on our map to illustrate the relationship between tectonic plates and seismic activity. They can  pull in a second data set and visualize it along side our original set of Data. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

To Accomplish it the following was done ..

-- Ploted a second data set on our map.

-- Added a number of base maps to choose from as well as separate our two different data sets into overlays that can be turned on and off independently.

-- Add layer controls to our map.



