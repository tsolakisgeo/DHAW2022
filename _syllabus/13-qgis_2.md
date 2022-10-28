---
class: 13
day: Firday, October 28
title:  (2/2)
tags: 
---

## Assignment due: 
- Upload a map by using the csv code we wrote in last class. Import it on QGIS, export a .jpg, and upload it on GitHub

## Notes 

#### Helpfull websites
- [EarthExplorer](https://earthexplorer.usgs.gov/). It requires registration. [Watch Obtaining + Loading Landsat Imagery in QGIS 3.10](https://www.youtube.com/watch?v=mBk2VIMawRE&ab_channel=MiddleburyRemoteSensing) for a step-by-step guide on how to use the data from EarthExplorer.
- [Mapping the Ancient Mediterranean with QGIS: A Quick Guide](https://sites.temple.edu/tudsc/2017/01/31/mapping-the-ancient-mediterranean-with-qgis-a-quick-gude/). From where you can download data on mapping data for the ancient world:
  - [Coastline](http://awmc.unc.edu/awmc/map_data/shapefiles/physical_data/coastline/)
  - [River](http://awmc.unc.edu/awmc/map_data/shapefiles/physical_data/ba_merge/)
  - [Inland water](http://awmc.unc.edu/awmc/map_data/shapefiles/physical_data/inlandwater/)
  - [Open water](http://awmc.unc.edu/awmc/map_data/shapefiles/physical_data/openwater/)
  - [Roman Road](http://awmc.unc.edu/awmc/map_data/shapefiles/ba_roads/)
- [ArcGIS REST Services Directory](https://server.arcgisonline.com/arcgis/rest/services). You can check the different MapServers. In order to download them
  - navigate to one MapServer and copy the link. E.g., https://server.arcgisonline.com/arcgis/rest/services/NatGeo_World_Map/MapServer
  - Go to QGIS. Right click on XYZ Tiles and Add Connection.
  - In Name, put a representative name.
  - In URL, paste the link you copied and add `/tile/{z}/{y}/{x}`.
  - Press OK. Then you will able to drap  and drop it in Layers.
  - [OpenDem](https://www.opendem.info/opendem_client.html). You can download contour datasets in shape format.
  - Ancient World Mapping Center(), that provides different resources for diggital mapping of the ancient world. You may want to check the Spapefiles in [Resources](http://awmc.unc.edu/wordpress/map-files/).