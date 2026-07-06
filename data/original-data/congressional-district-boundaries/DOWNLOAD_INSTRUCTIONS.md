# Congressional District Boundary Download Instructions

The congressional district boundary files used in this thesis are not included directly in this repository because the shapefile folders are too large for standard GitHub browser uploads.

The thesis uses U.S. congressional district shapefiles from the UCLA Congressional District Boundary Project:

https://cdmaps.polisci.ucla.edu/

These data provide digital boundary definitions for U.S. congressional districts and are organized for download by Congress in ESRI Shapefile format.

For this thesis, congressional district shapefiles were downloaded for each relevant redistricting period from 1980 through the present.

Users seeking to replicate the analysis should download the relevant congressional district shapefiles directly from the UCLA source and place them in this folder.

Each shapefile should be kept together as a complete set of related files. A shapefile usually includes several component files, such as:

- `.shp`
- `.shx`
- `.dbf`
- `.prj`
- `.cpg`

Do not separate these files, because they are required together for GIS and spatial intersection workflows. 
They will download into one folder. The recommendation is to keep them together in said folder, as seen in the coding flow also uploaded.

Suggested organization:

```text
congressional-district-boundaries/
    1980s/
    1990s/
    2000s/
    2010s/
    2020s/


Lewis, Jeffrey B., Brandon DeVine, Lincoln Pitcher, and Kenneth C. Martis.
Digital Boundary Definitions of United States Congressional Districts.
Los Angeles: UCLA Department of Political Science, 2013. Retrieved from https://cdmaps.polisci.ucla.edu/
