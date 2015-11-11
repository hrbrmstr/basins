# basins

Aggregated WorldBank river basin polygons &amp; ids

Initially made for [this SO question](http://stackoverflow.com/questions/33653914/mapping-geo-location-coordinates-or-city-to-worldbank-climate-api-river-basin) but this seemed generally useful. 

Two data files:

- `basins.geojson` : a GeoJSON file with all 468 river basin polygons mapped to world bank basin id's
- `basins.rda` : an R data file with `basin_list` (a list of individual polygons) and the `SpatialPolygonsDataFrame` that was used to create `basins.geojson`
