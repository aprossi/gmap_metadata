## Sample geopackages

The sample unprojected (geographic, MOON, IAU sphere) geopackages are supposed to work with [Mappy](https://github.com/europlanet-gmap/mappy), i.e. 
geologic units are defined as points, and polygons are generated dynamically as needed, based on contat intersections.
 
 ## Qgis project CRS
 
 ```
 GCS_Moon_2000
WKT
GEOGCRS["GCS_Moon_2000",
    DATUM["D_Moon_2000",
        ELLIPSOID["Moon_2000_IAU_IAG",1737400,0,
            LENGTHUNIT["metre",1]]],
    PRIMEM["Reference_Meridian",0,
        ANGLEUNIT["degree",0.0174532925199433]],
    CS[ellipsoidal,2],
        AXIS["geodetic latitude (Lat)",north,
            ORDER[1],
            ANGLEUNIT["degree",0.0174532925199433]],
        AXIS["geodetic longitude (Lon)",east,
            ORDER[2],
            ANGLEUNIT["degree",0.0174532925199433]],
    USAGE[
        SCOPE["unknown"],
        AREA["World"],
        BBOX[-90,-180,90,180]],
    ID["ESRI",104903]]
Proj4
+proj=longlat +R=1737400 +no_defs
Extent
-180.00, -90.00, 180.00, 90.00
```

