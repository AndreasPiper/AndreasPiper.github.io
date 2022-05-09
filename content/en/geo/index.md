---
title: "Geo data visualizations"
weight: 3
---


### Distance Map
In order to illustrate the differences in commuting behaviour, we decided to show some values in the form of a map with a breakdown by municipalities. The first map shows the average number of kilometers covered by a resident. It can be seen that in suburb municipalities of Copenhagen e.g. Brøndby, Glostrup, Ballerup and Lyngby-Taarbæk the average distance is around 4 kilometers and is higher than the total average (3.09). That can be caused by the fact that people decide to commute to the city with their bikes. The same pattern occurs in Syddjurs and Silkeborg where people may commute to Aarhus and in Faaborg-Midtfyn where people may commute to Odense. The clear outlier in that observation is the city of Aalborg and its suburbs where the average biking distance is significantly lower than in other urbanized areas.

{{< include-html "content\en\geo\distance_map.html" >}}

### Age Map
Additionally we see that the suburban areas tend to have a lower mean age on the bike commuters compared to the national average of 36.95 years. This is very clear in municipalities such as Egedal, Allerød, Rudersdal, Skanderborg and Horsens. All within 20-30 kilometers of center Copenhagen/Aarhus and having traffic problems in the commuting hours, making biking a faster option.  The areas far from larger cities have a much higher mean age. E.g. Odsherred (50.8), Langeland (45.4), Tønder (43.2) and Jammerbugt (42.4), since the bike rides primarily consist of leisure and shopping commutes rather than commutes for work or school.
{{< include-html "content\en\geo\age_map.html" >}}

### Education Map
We also wanted to check if the education status of average bikers across the country is similar. We had a suspicion that maybe in cities it may be lower as "wealthy homebuyers prefer to live in cities" cite(https://www.theguardian.com/money/2015/nov/15/wealthy-homebuyers-prefer-to-live-in-cities) and they can easily choose a car as the primary mode of transport. However, it can be seen that bikers in Copenhagen and Frederiksberg are well educated and still decided to use bikes to commute. The surprising fact that we discover is that the bikers living on Samso island are haveing the highest average education level.
{{< include-html "content\en\geo\edu_map1.html" >}}

### Heat Map
The heat map is a great way of presenting different hubs of similar behaviour across map. In this heat plot it is clear to see the 
<iframe src="https://AndreasPiper.github.io/geo/heat_map1.html"
	sandbox="allow-same-origin allow-scripts"
	width="100%"
	height="500"
	scrolling="no"
	seamless="seamless"
	frameborder="0">
</iframe>

### Hour Map
We also wanted to investigate if the geographical locations of municipalities impart the average time of departure among cyclist. However, by looking at the map above it is hard to find any pattern. Again Samsoe island is an outlier with the lowest average departure hour of 11:45.
{{< include-html "content\en\geo\hour_map1.html" >}}

