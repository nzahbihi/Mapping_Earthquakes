# Mapping_Earthquakes
## Analysis Overview
The purpose of this analysis is to map earthquake data, specifically from the past 7 days. We also added a map layer for tectonic plates, so that the user is able to review the frequency of the earthquakes along the tectonic plates. The map also includes a separate layer for major earthquakes (magnitude > 4.5) from the past 7 days.

## Resources
  * Data Sources: [USGS](https://earthquake.usgs.gov/earthquakes/feed/), [Tectonic Plate data](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
  * Software: Visual Studio Code 1.70.2.

## Results
Working with Leaflet and Mapbox to create the map, we mapped earthquake and tectonic plate data.

![Earthquake Map](https://user-images.githubusercontent.com/106129195/189452829-0de1283b-9e3b-43ba-a255-f8cd9aa4bc2e.png)

The user can toggle between the three sets of data, and change the map's appearance to their liking. The bubbles represent each recorded earthquake incident, and their sizes correlate with the magnitude of the earthquake. If the user clicks on a bubble, it will provide magnitude and location information pertaining to the earthquake.
