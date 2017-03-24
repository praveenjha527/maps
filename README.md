Maps
====

Repository for all spatial data.

For details go to pur project site at [http://projects.datameet.org/maps/](http://projects.datameet.org/maps/)

----
###Note on Format###

This Repository contains Geospatial Data in [Shapefile Format](https://en.wikipedia.org/wiki/Shapefile), which is the defacto format for most GIS software.

In case you want this data in GeoJSON or KML, or any one of the myrid Vector formats, you could use Gdal's [ogr2ogr](http://www.gdal.org/ogr2ogr.html) tool to convert these shapefiles to your prefered format. This can be done by the following commands:

`ogr2ogr -f GeoJSON <output name>.geojson <input name>.shp` &

`ogr2ogr -f KML <output name>.kml <input name>.shp`  &

`ogr2ogr -f LIBKML <output name>.kmz <input name>.shp`  

If you wish to convert these fiels using an Online too, you could look at: [MapSharper](http://www.mapshaper.org/); Do remeber to Zip up all the Files (*.shp, *.dbf, *.shx, *.prj) and import that into MapSharper. That way, you will get all attributes in the converted file.

