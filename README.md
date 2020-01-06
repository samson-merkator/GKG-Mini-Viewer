# GKG-Mini-Viewer
This repository contains html, CSS and javascript files for the GKG- Mini viewer
This is the GKG mini viewer
The mini viewer allow users to select predefined questions
The predefined questions are then used as a layer to querry the WMS of the GKG Geoserver
The returned layer from the GKG Geoserver querry is superimposed on the Map interface with transparency
The viewer also accepts input post code that is used to querry the Nederlands location API for the address of the post code.
The GPS location of the returned JSON is then extracted and injected as a zoom function to MapBox API.


