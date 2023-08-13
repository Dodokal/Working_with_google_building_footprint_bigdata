# Working_with_google_building_footprint_bigdata
Dask Geopandas Buildings Extraction

This code loads a CSV of building polygons, converts it to a Dask GeoDataFrame, clips it to an area of interest shapefile, and writes the clipped features to a shapefile.

# Code Overview
Load CSV to Dask DataFrame

Convert to Dask GeoDataFrame using geometry column

Set CRS to EPSG:4326

Read the area of interest shapefile and transform to same CRS

Clip Dask GeoDataFrame to area of interest

Compute clipped GeoDataFrame

Write clipped features to shapefile
# Requirements
dask

dask_geopandas

geopandas
# Usage
Update read_csv and shapefile paths to point to your data

Update output shapefile path
# Run script
This will generate a shapefile containing only the buildings within the area of interest.

# Credits
Uses the following open data:

Buildings CSV from HotOSM: https://sites.research.google/open-buildings/#dataformat

Area of interest shapefile
