## Geocoder
calculates coordinates for the given addresses.
calculates the distances between origin and destinations, assuming the first row of the dataframe as the origin
publish the output to webmap (in this case arcgis online)

## Repo contains
#### Data.csv: 
containing the addresses to be geocoded.
#### geocoder.ipynb: 
contains script for geocoding. function geo_coder() is a generic function which can be used elsewhere. function dist_cal() can be used for any spatial data frame where the distance from first row to all other rows in same df needs to be calculated.
#### visualisation.html: 
contains the output of the result.
#### thumbnail.png: 
contains a thumbnail for arcgisonline layer.
