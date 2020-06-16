# lexington_food_access
locations of grocery stores overlaid onto a heatmap of average income, by zip code

# Vision
Show on one map (not sure if it will be static or on Mapbox) the locations of grocery stores in Lexington AND median household incomes, by ZIP code. It will be a bunch of points layered on top of a chloropeth map.
I believe that these are the same kind of raw data used to generate this [Food Access Atlas by the USDA](https://www.ers.usda.gov/data-products/food-access-research-atlas/go-to-the-atlas/).

## Grocery store locations
OSM shows only one grocery store in all of Lexington (I searched by building and amenity). So, these data won't do. My plan is to generate a vector data file with pictures that I took from my computer screen after typing 'grocery store' in Google Maps (which uses EPSG: 3857), following the steps outlined in Module 06.

## Median household income by ZIP code
 - I think I can use the shapefiles from [data.gov (TIGER) website](https://catalog.data.gov/dataset/tiger-line-shapefile-2019-2010-nation-u-s-2010-census-5-digit-zip-code-tabulation-area-zcta5-na).
 - I can join tabular [income data] (https://www.psc.isr.umich.edu/dis/census/Features/tract2zip/) to the above geometry data, using the instructions in Module 04.