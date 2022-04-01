# Mapping Earthquakes
## Overview of the project:
The purpose of the project was to build interactive maps using GeoJSON data for earthquakes in the last 7 days. 
## Resources:
* Javascript, HTML, VS Code 1.51.1
* Mapbox
* Leaflet.js
## Result:
I built an earquake visualization tool which retrives GeoJSON data from earthquake.usgs.gov and build markers for past 7 days' of earthquake on the map . Radius and color of the marker depends on the magnitude of the earthquake. Also, there are popups for every marker with location and magnitude info.

The Map
The interactive map has been designed to have a toggle where the user(s) can switch map views (street, satelite, dark). User(s) can also choose which levels of data to be displayed by turning the selection on and off. The available display options are shown below:

![Streetview with earthquakes](https://user-images.githubusercontent.com/96354508/161194942-38e62709-f0f9-40e2-a090-e14a9daa34ef.png)

Displays all earthquake data in Streetview

![Satelliteview with Techtonic Plates](https://user-images.githubusercontent.com/96354508/161195012-1cd66db4-ed11-432b-a168-4b3d5ba84de4.png)

Displays satellite view of all earthquakes and techtonic plates

![image](https://user-images.githubusercontent.com/96354508/161194849-41064bce-0e9d-4d31-9f25-ef70071d04d4.png)
Display of major earthquakes in dark view
