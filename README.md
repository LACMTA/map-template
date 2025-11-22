# map-template

## Templates

[Metro-branded ESRI map example](https://lacmta.github.io/map-template/metro-branded-esri-map/)

## Instructions

This map uses Leaflet and ESRI's Leaflet extensions.  It pulls in two geospatial data sources from Metro's ArcGIS Online:

* A vector tile basemap styled with Metro's branding
* A raster tile layer with Metro's bus and rail network with stations and station labels

This repository's live example uses an ESRI API key limited to this page.  To use these layers, you will need to request an API key for your own page from Metro's DX team and update the `ESRI_KEY` value in the code.