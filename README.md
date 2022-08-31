# Mapping Earthquakes

Creating interactive maps using Leaflet.js library, Javascript, and HTML to retrieve earthquake information from a GeoJSON file and plot the results in a visual format.

# Overview

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. We wrote a script to pull the GeoJSON earthquake data from the USGS website to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven days. The data is then added to a map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts are built using JavaScript and D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We then used Leaflet library to plot the data on a Mapbox style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display Tectonic plates, Earthquake magnitude and location information.

Throughout this project, we learned how to create map layers, visual customizations that included:

* Toggling between map styles (i.e. dark, streets, satellite)
* Color changes to lines, marker types, and sizes
* Adding popup info box
* Plotting different points, multiple points, lines, polygons

# Examples

## Map Style = Dark with circle marker and popup info box

![marksrs_popups](https://user-images.githubusercontent.com/103727169/187363737-4043b494-a43e-406d-8b26-0b588ae1074b.png)

## Map Style = Navigation Preview Light with dashed line mapping (5) location points

![mapping_lines](https://user-images.githubusercontent.com/103727169/187363801-9f2cc154-50ba-40ff-b3a3-826b34d32aa2.png)

# Challenge Submission
(files can be found [here](https://github.com/munno88/Mapping_Earthquakes/tree/main/Earthquake_Challenge))

## Deliverable 1: Add Tectonic Plate Data

![deliverable1](https://user-images.githubusercontent.com/103727169/187363883-a327238e-41fb-433b-b0a8-353c45b6cb36.png)

## Deliverable 2: Add Major Earthquake Data

![deliverable3](https://user-images.githubusercontent.com/103727169/187364093-2cb004ea-601b-4694-850b-87232f8e437a.png)

## Deliverable 3: Add an Additional Map

![additionalmap](https://user-images.githubusercontent.com/103727169/187364148-af9d4b97-cf89-4a37-81f4-8ace47730557.png)

***Interactive map can be access through this [link](https://munno88.github.io/Interactive-Earthquake-Map/).***
