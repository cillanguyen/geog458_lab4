# GEOG 458 Lab 4: Map Design and Tile Generation

In this section we will introduce how to load online map service as a map layer, and then convert the map layer as a tileset in QGIS 3. To do this, you need to install the QGIS plugin QMetaTiles.

## Map 1: San Jose

In this first map I have decided to have the map located in San Jose. Because I want to explore
more on the solar power systems in San Jose. Since solar power is commonly used in this area.
For the projection of the map I color the map dark blue to focus on the surrouding area only.

While trying to display the map, the map doesn't seem to be connecting to the final map.
I'm not sure if it could be how the QTiles were downloaded. But the overall code seems right.

# Map 2: Solar Power in California per sqft

In this second map I have decided to have teh map located in San Jose. But using the State of
California solar power dataset. This measures the solar power based on sqft. I color coded
the solar power sqft by the measure of the sqft. This is because I wanted to emphasize on the
area image of in San Jose.

For the map projection I went with a light map to focus on the sqft of solar power around San Jose.
I used QGIS to put the dataset on to the map, after that I downloaded the file as a QTiles. I changed
the zoom in and out so that less images would be displayed.

Same as Map 1 the map couldn't be dispalyed. It might be because of the code, but the code is
correctly inputted.

# Map 3: San Jose Map with the Solar Power Map

With this map I just combined map 1 with map 2. With the use of QGIS. This help emphaize on the
display of the map.

Same as Map 1 I couldnn't display the map properly.

# Map 4: Lakes in San Jose

With this map. I made some changes to the mapbox map. I removed the highways/freeways. Changed the color
of the water/lakes to emphaize on the focus on the map which is the lakes. This map has more color and more
color focus on nature. With the dataset on top of that, I color coded based on the sqft of the lakes as
well. So the color coded is based on the range of color from white to red. Red meaning that the sqft of the lakes
are a lot bigger. After I used QGIS to combine the Lakes dataset from State of California. Then I used QTiles
to get the tiles of the map.

Same as the Map 1 the map couldn't be displayed properly on the final map.