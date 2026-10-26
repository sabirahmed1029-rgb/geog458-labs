# geog458-labs
Lab exercises for GEOG 458: Digital Geography
# Seattle Elevation and Rivers

## Purpose
This interactive map shows elevation and rivers and streams in Seattle and King County, Washington.

## Data Sources
- Basemap: Custom Mapbox Studio style.
- Elevation: USGS 3DEP 1-meter elevation data.
- Rivers and streams: King County GIS.

## Processing
Elevation data was styled in QGIS using Singleband pseudocolor and the RdYlGn color ramp. The basemap and elevation raster were exported separately as PNG tile pyramids using QMetaTiles at zoom levels 8–12. River data was exported as GeoJSON and displayed as blue lines with clickable watershed and basin popups.

## Measurements and Estimates
The elevation layer uses USGS elevation data. It is not an IDW interpolation or an estimate between monitoring stations.

## Map
The map includes an interactive elevation overlay, a legend, navigation controls, and river popups.

## Links and Screenshots
- Repository: [(https://github.com/sabirahmed1029-rgb/geog458-labs/tree/main/lab3)]
- Lab 3-1: [(https://sabirahmed1029-rgb.github.io/geog458-labs/lab3/sabirahmed_lab3-1.html)]

- Lab 3-2: [Add GitHub Pages URL]
- Screenshots:

### Elevation and Rivers Map
![Elevation and Rivers Map][(Screenshot%202026-10-25%20at%207.54.25%20PM.png)]

### River Popup
![River Popup][(Screenshot%202026-10-25%20at%207.54.34%20PM.png)]
