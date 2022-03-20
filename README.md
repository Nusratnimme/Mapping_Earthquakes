# Mapping Earthquakes

## Overview

Disaster reporting network, a nonprofit company, provides information on disaster around the world. They wanted to visualize data with interactive maps using GeoJSON data on earthquakes.

### Resources

- Data sources: Earthquakes GeoJSON data was retrieved from USGS survey website and tectonic plates data using "GeoJSON/PB2002_boundaries.json" from a github repository.

- Softwares: VS Code, JavaScript, D3, Mapbox and HTML.

### Purpose

The main purpose of this project is to visualize the  earthquakes GeoJson data of different magnitudes for the last seven days.

## Results

Using JavaScript and D3.json libraries retrieved the latest earthquakes data and plotted them on a Mapbox map with an API request. Later some interactive features were added to the map to illastrate the data visualization on earthquakes.

### Adding Earthquake and Tectonic Plates Data

To complete this project, used a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. With this initial map, tectonic plates data were used to show the relation between the location and the seismic activity. Both data were then added to the map.

On the map the magnitudes and location of each earthquake was shown in a popup circle marker. The radius of the markers reflected the magnitudes of the earthquake in their size and color.

The map was shown below after adding the earthquakes and tectonic plates to the GeoJson layer.

![EQ_Tectonic_plates](https://github.com/Nusratnimme/Mapping_Earthquakes/blob/main/Images/Tectonic_Plates.png)


### Adding Major Earthquakes Data

Major earthqakes data  with magnitude more than 4.5 were retrieved and added to the map.

Three datasets were added to the map layers as **Earthquakes**, **Tectonic plates** and **Major Earthquakes** respectively.

![Major_EQ](https://github.com/Nusratnimme/Mapping_Earthquakes/blob/main/Images/MajorEQ.png)

### Additional Map
Using JavaScript and Leaflet.js, added a third map style to the earthquake map as **Dark** with **Streets** and **Satellite**.

The following image showing the map.

![Dark_Style](https://github.com/Nusratnimme/Mapping_Earthquakes/blob/main/Images/Additional%20map.png)
