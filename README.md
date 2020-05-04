# labelbox-tiled-examples
A repository of JSON examples for using XYZ Tile Layers in Labelbox. Tile layers were created from open source geospatial data using mostly QGIS 3.

For a brief overview of Tiled Imagery and how it relates to Labelbox, please see our documentation page here (https://labelbox.com/docs/geospatial/tiled-imagery).

The examples shown are taken from various open source datasets. Vector and raster-based geospatial data is first tiled using QGIS 3 `Generate XYZ tiles(Directory)`.

For information on how use QGIS to tile imagery or other datasets please see this loom video: https://www.loom.com/share/0534bc5847ca407781a4c4ebfe0e0add

S3 Bucket link where all examples are stored: https://s3.amazonaws.com/lb-tiler-layers

Tiled Imagery in Labelbox is a Slippy Map tool that you can use for labeling map tiles of the earth at various zoom levels. Slippy Map is a term referring to modern web maps that let you zoom and pan around. Not only can you use open source slippy maps with already generated URLs (Mapbox, etc.), but it is possible to convert geospatial data into slippy maps for use as Tile Layers in Labelbox. Some examples of data to be tiled include:

- Synthetic Aperture Radar (SAR) imagery
- GeoJSON, ESRI Shapefile vector data
- Multi-spectral and RGB satellite imagery

