# GIS 3 - Lab7
## Author: Çağlayan Bal
### Date: 05/15/2022

I created a heatmap of the Covid-19 testing sites in Chicago in Mapbox.\
The link to the map is:\
https://api.mapbox.com/styles/v1/balcaglayan/cl36h23y2000m14qnvugb1bfc.html?title=view&access_token=pk.eyJ1IjoiYmFsY2FnbGF5YW4iLCJhIjoiY2wzNmQ2b3JuMDlkaTNkbHBtZXByZ2dlZiJ9._GSXSwyqDbKccQ7WXR76sw&zoomwheel=true&fresh=true#11.94/41.85977/-87.70716

I pulled the dataset from the Chicago Data Portal:\
https://data.cityofchicago.org/Health-Human-Services/COVID-19-Testing-Sites-Map/j2wj-wjrp

My goals include:
-	To better understand the distribution of Covid-19 testing sites in Chicago visually by creating a heatmap;
-	To better understand which community areas in Chicago have more testing sites or which have fewer by overlaying the heatmap with the community area boundaries;
-	To provide easy access to the address information of each testing site by adding the addresses as labels to the map.

I was inspired by the Chicago Trees Map and the quick-start guide to Mapbox. I used a different dataset for my map, the location of the Covid-19 testing areas. I chose a paler base map to better highlight the data. Instead of data-driven circles, I used the heatmap option to see the density of the testing areas in Chicago. I changed the opacity and the size of the features to improve the visualization. Besides, I added the community area boundaries as a choropleth map to better show the distribution of testing areas across Chicago by changing the color and opacity. Finally, to add the addresses of each testing site as a label to the map, I added the data as a component by selecting the data visualization type as T symbols.
