# cwmi-garden-map

This is a Leaflet map to replace the old Carto map at https://compost.css.cornell.edu/communitygardenmap.html

The files in this repo were originally generated using the qgis2web plugin for QGIS.  These files were then heavily edited to match the map style of the old map, remove unneeded components, and pull the data directly from the [Community Garden on the Map](https://docs.google.com/spreadsheets/d/1N5XtWV4jpIbf8RPEVgynpC-DwTJj4qdss6cXQQ-Ciss/edit?usp=sharing) Google spreadsheet.  Community gardens can be added or edited in that spreadsheet, and this map will automatically update.

This map can be embedded in a webpage using the following HTML code:

```
<iframe style="height: 700px; width: 100%; border:none" src="https://cornell-gis.github.io/cwmi-garden-map/" allowfullscreen></iframe>
```