# ForestGIS - Sandbox for GIS

## Purpose
A small project to learn the foundations of GIS.

Techniques and applications used are:

- QGIS

- QGIS Cloud

- PostgreSQL

- PostGIS

Links to maps are available at https://thomasostensson.github.io/forestGIS/

Note: The target audience for this project is Swedish, therefore Swedish is the primary language used in the maps and documentation.


## Data

Only open data from Swedish authorities are used

Skogsstyrelsen and Lantmäteriet:



## Method

1. Import data to QGIS.

2. Trim data to correspond to the geographical externt of Sundsvall Municipalty, Sweden.

3. Apply background map for orientation: 

4. Calculations and comparisons using SQL (e.g. st_intersect) and raster manipulation if applicable.

5. Compress data to conform to QGIS database space limitations (i.e.reduce map size to fit within the storage space that QGIS Cloud Free provides).

6. Upload to QGIS Cloud


## Result

The expected results varies from map to map. 

None of the maps present a total and correct answer to anything, further analysis and comparisons of the data presented is required. 

Note: Due to the amount of compression used when preparing the maps, the data is likely unusable for any real analysis. This project is intended for experimentation and learning purposes only.