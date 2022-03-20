# Mapping Earthquakes

## Overview

Disaster Reporting Network, a nonprofit company, provides data-driven stories on disasters around the world. They want to visualize Earthquake data using interactive and easy to use maps.

### Resources

- Data sources: Earthquakes GeoJSON data extracted from US Goelogical Survey (USGS) website; Tectonic plates data "GeoJSON/PB2002_boundaries.json" from a github repository.

- Software: VS Code, JavaScript, D3, Mapbox, and HTML.

### Purpose

The main purpose of this project is to visualize data on earthquakes in the last seven days on an interactive map.

The map should be user-friendly and contain information on the location and magnitude of the earthquakes. Fault lines should be layered on the map. Bubbles indicating magnitude of corresponding earthquake through size and color should be added to the map.

## Results

### Earthquake and Tectonic Plates Data

Using an URL, earthquake data containing geographical coordinates and the magnitudes of earthquakes for the last seven days was downloaded from the USGS website. Next, tectonic plates data were used to show the relation between locations and seismic activity. Both data were then added to the map.

Magnitudes and location of each earthquake was shown in a popup circle marker. The radius and color of the markers reflected the magnitudes of the earthquakes.

The resulting map was as below:

![EQ_Tectonic_plates](https://github.com/Nusratnimme/Mapping_Earthquakes/blob/main/Images/Tectonic_Plates.png)


### Major Earthquakes Data

Major earthqakes, defined as having a magnitude of more than 4.5 were filtered out and displayed on the map.

So, three layers were added to map, namely **Earthquakes**, **Tectonic plates** and **Major Earthquakes**.

The resulting visualization after this step was as below:

![Major_EQ](https://github.com/Nusratnimme/Mapping_Earthquakes/blob/main/Images/MajorEQ.png)

### Additional Map
Using JavaScript and Leaflet.js, a third map style was added to the earthquake visualization as **Dark** with **Streets** and **Satellite**.

Below image shows the output:

![Dark_Style](https://github.com/Nusratnimme/Mapping_Earthquakes/blob/main/Images/Additional%20map.png)

