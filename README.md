# U-District Boba Tea Stores Maptiles

####Introduction
This map is presenting the information of **Boba Tea Stores** within the **U-District of University of Washington in Seattle**. There is *pop up function* in the map showing:
- name of the store
- whether has games within
- whether sells sweets beside boba tea

####Working Process
The self-generated dataset is done on **MapBox** with geolocation provided by *Yelp*. The dataset was converted into tiles and putted as a layer to a basic style template and published. The map tiles are exported by QMetaTiles in QGIS with maximum zoom level of **18**.  Finally, a OpenStreetMap was added as basemap and combined with the maptiles. 
