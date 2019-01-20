# House Price Index & Venues in Istanbul
## Description & Disscusion of the Background
Istanbul is one of the largest metropolises in the world where over **15 million** people live and it has a population density of **2.813** people per square kilometer. As a resident of this city, I decided to use Istanbul in my project. The city is divided into **39** districts in total. However, the fact that the districts are squeezed into an area of approximately **72** square kilometers causes the city to have a very intertwined and mixed structure [1].

As you can see from the figures, Istanbul is a city with a high population and population density. Being such a crowded city leads the owners of shops and social sharing places in the city where the population is dense. When we think of it by the investor, we expect from them to prefer the districts where there is a lower real estate cost and the type of business they want to install is less intense. If we think of the city residents, they may want to choose the regions where real estate values are lower. At the same time, they may want to choose the district according to the social places density. However, it is difficult to obtain information that will guide investors in this direction. 

When we consider all these problems, we can create a map and information chart where the real estate index is placed on Istanbul and each district is clustered according to the venue density.

## Data Description
To consider the problem we can list the datas as belows
* I found the Second-level Administrative Divisions of the Turkey from Spatial Data Repository of NYU [2]. The .json file has coordinates of the all city of Turkey. I cleaned the data and reduced it to city of Istanbul ([Here is my .json file](https://github.com/Srcanyildiz/istanbul/blob/master/istanbul_geo_1.json)) where I used it to create **choropleth** map of House Index of Istanbul.
* I used **Forsquare API** to get the most common venues of given Borough of Istanbul [3].
* There are not too many public datas related to demographic and social parameters for the city of Istanbul. Therefor you need create your own data tables. In this case, I collected latest House Price Averages ([Here is my datas](https://github.com/Srcanyildiz/istanbul/blob/master/istanbul_geo.csv)) for each Borough of Istanbul from housing retail web page [4].
* I used **Google Map**, 'Search Nearby' option to get the center coordinates of the each Borough. ([Here is my datas](https://github.com/Srcanyildiz/istanbul/blob/master/istanbul_geo.csv)) [5].

### References:
* [1] [Istanbul - Wikipedia](https://en.wikipedia.org/wiki/Istanbul)
* [2] [Second-level Administrative Divisions of the Turkey](https://geo.nyu.edu/catalog/stanford-nj696zj1674)
* [3] [Forsquare API](https://developer.foursquare.com/)
* [4] [House prices for each Borough from "Hurriyet Retail Index for 2018"](https://www.hurriyetemlak.com/Emlak-Endeksi/Detayli-Analiz/Istanbul)
* [5] [Google Map](https://www.google.com/maps/)

