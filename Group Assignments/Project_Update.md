# Project Update
https://github.com/robynbwong/Group-Assignments/blob/main/Group%20Assignments/README.md 

## Status
Based on the advice from Yoh and Bo, as well as my own difficulties trying to use the Farmland dataset, I will be changing course a little bit. The CCED data is easy to use so I will keep using that. I also found a good census dataset that has how much of the county's population is urban versus rural, which I think is an interesting connection to land conservation.

This past week, I tried to research how to rasterize vector data in an attempt to do something with the Farmland dataset but I did not understand any of the guides. I tried to do it in QGIS but did not understand how people know what pixel size or scale to do. I tried to open the shapefile with geopandas in jupyter hub just to take a look at the data and it was too big for the notebook memory. So I looked at it a bit as a csv file with pandas, but after doing the basic data exploration I didn't know what else to do with it. 
## Data
As mentioned in the previous section, I have downloaded a new dataset that I think is more manageable for me. It has the percentage of the county's population that resides in "urban" versus "rural" places, and breaks down the kinds of urban concentration into two categories. I exlpored it today and got rid of extra columns, as well as saw what the most and least urbanized were. 
https://github.com/robynbwong/Group-Assignments/blob/main/Group%20Assignments/data/urb.rural.counties.csv

I had previously done an exploration of the CCED dataset for the Week 2 Assignment. I tried just now to put the CCED shapefile in Github but it said the file was too big.

## Major Concerns
### 1 
First, not being able to use the data I originally wanted to. But, the census dataset I got should be fine for me to use.
### 2
Second, I don't really understand how to make maps with categorical data. All the examples we have from class are interval-ratio and all the examples of folium are chloropleth maps. Honestly, I think this is a bigger issue for me than changing my scope a little bit. I tried to make a map to show different categories of the easement holders from my CCED but the code I tried to copy had all this stuff about making a custom legend and colors first and it made me confused. I would really like to see an example of this in class. I also am a little unsure of how to make a visualization that shows two different things overlayed, rather than just one chloropleth (like the percent black population one in class). For instance, to overlay the polygons of the easements with the chloropleth of percent urban population
## Minor Concerns
### 1
I don't know how I am supposed to submit my jupyter notebook and the data so you can run it if the CCED file won't upload. Maybe it was a one-time problem? It seems like people probably upload much bigger files in github...
