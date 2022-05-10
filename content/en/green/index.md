---
title: "Green conclusion"
weight: 5
---
<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

### Green development

Looking at all the bike trips in the dataset, we were interested in exploring the development in the use of bicycles to see if there has been an increase in this clean mode of transport. Moreover, we wanted to investigate whether there has been an increase in the use of electric bikes, since these are a great alternative for commuting by car if your don't want to break a sweat on your way to work. Hence, E-bikes can help fight global climate change [1]. In fact, research studies suggests that using an electric bike could have a positive impact on the environment. A recent study by Ian Phillips et al. concluded that e-bikes have the capability to reduce car CO2 emissions by 24.4 million tonnes a year in England [2]. 

In the interactive plot below shows the number of bike trips by year showing the eight different bicycles types that are represented in the dataset. Notice that the question of bicycle type has only been included in the Danish National Travel Survey since 2014, hence years on the x-axis ranges from 2014-2021. It is obvious that the ordinary two wheel bike is by far the most dominant bicycle type. Zoom in on the remaining curves to see that E-bikes and Christiniabicycles are the second- and thirdmost popular types, respectively. The other  bike types have a very low number of counts in the range of 0-20 observations per year. This plot allows you to toggle on the curves you want to see by selecting or deselecting the bike types in the legend. 

{{< include-html "content/en/green/bike_type_part1.html" >}}

We're interested to see if there has been an increase in the use of bicycles and especially in the use of E-bikes. From the plot above it certainly looks like there has been a slight increase, but it cannot be stated with certainty from the absolute numbers. In the plot below, we solve this problem by looking at the percentage increase in the number of bike trips, ***x***, since 2014. Calculated for year ***i*** and bicycle type ***b***:

<div>$$\frac{x_{b,i} - x_{b,2014}}{x_{b,2014}} \cdot 100$$</div>

Note that when comparing percentage increase since 2014 we assume that the total number of bike trips per year stays roughly constant. The use of Christianiabicycles has increased significantly (800%) from 2014 -2021! The E-bikes has also become more popular with 5-fold increase compared to the 2014 baseline. Interestingly, the ordinary two wheel bike retains its popularity, but it does not seem to be used more often. The same story goes for the remaining bicycle types.

{{< include-html "content/en/green/bike_type_part2.html" >}}

### Discussion and conclusion

The dataset from the Danish National Transport Survey database contains much more data than what we have filtered out in this project. We have chosen to focus on bicycle trips, however, the dataset also contains trips by other modes of transport, for example car, public transport, a combination of those etc. Hence, there is potential for much further analysis. For example, one could investigate the trends in the use of different modes of transport and compare the development in bicycle habits in this perspective. Such analysis would give a more thorough to the answer we tried to answer above: Has there been an increase in the use of bicycles?

One limitiation to the dataset is the geospacial resolution. Locations are given by municipality or city codes, hence we don't have the information of longitude and latitude that is necessary for some geodata representations. On the other hand, the dataset has the advantage that it contains detailed social data which we have exploited in our demagraphic analysis and machine learning predictions. This adds a social dimension to the analysis of Danish bicycle habits which has deepened our understanding of who and why people bike. Gaining insights into how people tend to use different modes of clean transport is an important step towards reducing CO2 emissions in the transport sector, and we truly believe that cycling can help fight climate change.

References:<br/>
[1] The Green Machine: can E-bikes help fight climate change? [Cycleguard.co.uk](https://www.cycleguard.co.uk/how-green-are-ebikes)

[2] Ian Philips, Jillian Anable, Tim Chatterton. E-bikes and their capability to reduce car CO2 emissions. Transport Policy. Volume 116 (2022). Pages 11-23. DOI: https://doi.org/10.1016/j.tranpol.2021.11.019.
