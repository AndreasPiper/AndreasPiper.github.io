---
title: "Geo data visualizations"
weight: 3
---


### Distance Map
In order to illustrate the differences in commuting behaviour across Denmark, we decided to show some values in the form of a map with a breakdown by municipalities. Thanks to muncipaliteis codes available in data and geojson data [1] is was possbile to map servel interesting properties. 
In the first map the average number of kilometers covered by a commune resident. It can be seen that in suburb municipalities of Copenhagen e.g. Brøndby, Glostrup, Ballerup and Lyngby-Taarbæk the average trip distance is around 4 kilometers and is higher than the total average of 3.09. That can be caused by the fact that people decide to commute to the city with their bikes. The same pattern occurs in Syddjurs and Silkeborg where people may commute to Aarhus and in Faaborg-Midtfyn where people may commute to Odense. The clear outlier in that observation is the city of Aalborg and its suburbs where the average biking distance is significantly lower than in other urbanized areas. 

{{< include-html "content\en\geo\distance_map.html" >}}

### Age Map
After observing some patters in distance covered by danish inhabitants, next property that appeared interesting to us was the average age of the cycler. It can be observed on the map below that the suburban areas tend to have a lower mean age on the bike commuters compared to the national average of 36.95 years. This is very clear in municipalities such as Egedal, Allerød, Rudersdal, Skanderborg and Horsens. All within 20-30 kilometers of center Copenhagen/Aarhus and having traffic problems in the commuting hours, making biking a faster option.  The areas far from larger cities have a much higher mean age. E.g. Odsherred (50.8), Langeland (45.4), Tønder (43.2) and Jammerbugt (42.4), since the bike rides primarily consist of leisure and shopping commutes rather than commutes for work or school.
{{< include-html "content\en\geo\age_map.html" >}}

### Education Map
We also wanted to check if the education status of average bikers across the country is similar. And as education level is correlated with earnings [2]. We had a suspicion that maybe in cities it may be lower as wealthy homebuyers prefer to live in cities [3] and they can easily choose a car as the primary mode of transport. 

 Knowing that people living in big cities are more likely to be educated [4]. It can be seen that bikers in Copenhagen and Frederiksberg still decide to use bikes to commute. The surprising fact that was discover is that the bikers living on Samso island are having the highest average education level, which acctually contradicts the initial assumption. 
{{< include-html "content\en\geo\edu_map1.html" >}}


### Hour Map
Next the aspect of time was taken into consideration. It has been assumed that in the northen muncipalities, where the temperature is on average is the lowest [5] people will be more likely to cycle at later hours. However, by looking at the map belon it is hard to find any pattern. The only surprising thing again is the island of Samosoe where the average departure hour is lower. As they say "Early to bed and early to rise makes a man healthy, wealthy and wise." might be the case here.
{{< include-html "content\en\geo\hour_map1.html" >}}
### Heat Map
Last but not least, the data has been presented in form of a heat map. For that purpose the dataforsyningen API [6] has been used to pair muncipaliteis with approperiate geographical cords to populate the map. Unsurprisingly people cycle the most around towns. Copenhagen and its surrounding area are the most frequented among cyclists. Then Aarhus, Odense, and Aalborg can be observed as places where the concentration of cyclists is also at a high level. An interesting place on the map is the city of Randers. Even though that area is highly populated it is not popular among cyclers.

 
<iframe src="https://AndreasPiper.github.io/geo/heat_map1.html"
	sandbox="allow-same-origin allow-scripts"
	width="100%"
	height="500"
	scrolling="no"
	seamless="seamless"
	frameborder="0">
</iframe>

References: 

[1] Danish municipalities geoJSON, Magnus Larsen https://raw.githubusercontent.com/magnuslarsen/geoJSON-Danish-municipalities/master/municipalities/municipalities.geojson

[2] Blaug, Mark. “The Correlation between Education and Earnings: What Does It Signify?” Higher Education 1, no. 1 (1972): 53–76. http://www.jstor.org/stable/3445959.

[3] Wealthy homebuyers prefer to live in cities, The Guardian, https://www.theguardian.com/money/2015/nov/15/wealthy-homebuyers-prefer-to-live-in-cities

[4] The lure of big cities for the highly educated, Edith S. Baker, https://www.bls.gov/opub/mlr/2016/beyond-bls/pdf/the-lure-of-big-cities-for-the-highly-educated.pdf

[5] Observed Climatology of Mean-Temperature 1991-2020 Denmark, Climate Change Knowledge Portal, https://climateknowledgeportal.worldbank.org/country/denmark/climate-data-historical

[6] Dataforsyningen https://dataforsyningen.dk/
