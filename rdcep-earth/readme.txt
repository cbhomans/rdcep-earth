This is a prototype front-end for a climate data visualization engine. It accepts geoTIFF files (corresponding to a single scalar variable defined over the globe), renders them as contour plots on a manipulable 3D globe, and allows animation. Open RDCEPEarth.html to launch the visualization. Select a GeoTIFF or collection of GeoTIFF files in the GUI, then press play to animate. Use the slider to adjust animation speed.

The "js" subdirectory contains the javascript files.
main.js contains the main javascript controlling the visualization. helper.js contains a suite of helper functions, some externally sourced (see comments in file).

The "data" subdirectory contains the GeoTIFFs visualized as well as corresponding NetCDF files (for reference purposes), as well as coastline data in geoJSON format.

Inspired by earth.nullschool.net (see also: github.com/cambecc/earth)
