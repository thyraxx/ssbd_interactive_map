# ssbd_interactive_map
Serious Sam Bogus Detour interactive map.

A interactive map made with Leaflet fully map in javascript so it can also be run locally without connection for Serious Sam Bogus Detour, with all the experience stars. 
No secrets/easter eggs are currently on there.

To create the map tiles for a game map I used gdal2tiles `gdal2tiles.py --processes=10 --xyz -p raster --zoom=7 totalimage.png bogus_complete_map`

The complete image is split up in 4 zips because the complete image was 260~MB
