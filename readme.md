# ForestGIS - Sandbox for GIS

## Purpose
A small project to learn the foundations of GIS.

Techniques and applications used are:

- QGIS

- QGIS Cloud

- PostgreSQL

- PostGIS

Note that the target audience for this project is swedish, therefore swedish is the main language used.


## Data

Using only open data from Swedish Skogsstyrelsen and Lantmäteriet:



## Method

1. Import data to QGIS (Captain Obvius says Hi! :-D)

2. Trim data to correspond to the geographical externt of Sundsvall Municipalty, Sweden.

3. Apply background map for orientation: 

4. Calculations and comparisons using SQL (ex. st_intersect) and raster manipulation if applicable (perform calculations and change color of bands)

5. Compress data to conform to QGIS database space limitations (in practice: make the maps small enough to fit in the storage space that QGIS Cloud Free provides).

6. Upload to QGIS


## Result

The expected results varies from map to map. 

And, neither of the maps present a total and correct answer to anything, further analysis and comparisons of the data presented is required. 

Note that the amount of compression used when compling the maps likely makes the data unusable for any real analysis; this project is for experimentayion purposes only, not to present a useful result.