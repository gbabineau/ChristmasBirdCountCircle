# ChristmasBirdCountCircle
files for building a Christmas Bird Count Circle in Google Maps including sectors and routes

## Getting your data
Obtain circle information from https://audubon.maps.arcgis.com/apps/View/index.html?appid=fadfb421e95f4949bde20c29a38228bd

For example

```kml

Location: Charlottesville
Abbrev: VACA
Compiler: Xxxxx Xxxxx
Email: xxxx@xmail.com
Location: (-78.57, 38.07)
Count Date: 12/16/2018
```

##  Create a circle layer 
https://www.fcc.gov/media/radio/circleplot

+ Input your circle’s center lat/long
+ Input your radius in miles (7.5)
+ Name your circle, set the color if desired
+ click Create KML file (circleplot.kml)

## Create a map in mymaps.google.com

Import the layers you need

## How to create lines that follow roads that are not "driving route"

mymaps lets you create lines that follow roads as driving routes which is really useful but you can't do much with them when done if they are not for driving. For example
our circle has "sectors" that are road boundaries. But this can work.

Add a layer as a driving route for all the lines that have to follow a road. Because googlemaps makes these blue and limits the number of layers, you will have to save each layer as a separate KML file and then use a text editor to pull them all into the same KML file (copy each linestring generated into the same file). You will also have to make all the styles the same if needed

## Example results
https://drive.google.com/open?id=1uGY-H8ou61bT7pTo05MZhQ6v0NAl1FOr&usp=sharing
