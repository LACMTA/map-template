# map-template

## Templates

[Metro-branded ESRI map example](https://lacmta.github.io/map-template/metro-branded-esri-map/)

## Instructions

This map uses Leaflet and ESRI's Leaflet extensions.  It pulls in two geospatial data sources from Metro's ArcGIS Online:

* A vector tile basemap styled with Metro's branding
* A raster tile layer with Metro's bus and rail network with stations and station labels

This repository's live example uses an ESRI API key limited to this page.  To use these layers, you will need to request an API key for your own page from Metro's DX team and update the `ESRI_KEY` value in the code.

## Official layers

The cartographic layers show the routes side by side rather than overlapping.  They are updated as the network expands so using these layers will always display the current state of the system.

* [Map with authoritative cartographic layers](https://lametro.maps.arcgis.com/home/item.html?id=55946c3a313b4c8390be06995f5f7f09)
  * [Custom Basemap](https://lametro.maps.arcgis.com/home/item.html?id=bfc3028afac341499c40b8d2364db6c9)
  * [Metro Rail & Busway cartographic layer](https://lametro.maps.arcgis.com/home/item.html?id=17fc6859e51e4188b4a4120fcbd2e43d)
  * [Amtrak & Metrolink cartographic layer](https://lametro.maps.arcgis.com/home/item.html?id=f753bae7556844c2802022f6a3849b2d)
 
Line extension data will have to be pulled in separately before the new segments open.
