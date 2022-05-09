---
title: "Green conclusion"
weight: 5
---
<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

### Green development

Looking at all the bike trips in the dataset, we were interested in exploring the development in the use of bicycles to see if there has been an increase in this clean mode of transport. Moreover, we wanted to investigate whether there has been an increase in the use of electric bikes, since these are a great alternative for commuting by car if your don't want to break a sweat on your way to work. Hence, E-bikes can help fight global climate change [source](https://www.cycleguard.co.uk/how-green-are-ebikes). In fact, research studies suggests that using an electric bike could have a positive impact on the environment. A recent study by Ian Phillips et al. concluded that e-bikes have the capability to reduce car CO2 emissions by 24.4 million tonnes a year in England [source](https://www.sciencedirect.com/science/article/pii/S0967070X21003401). 

In the interactive plot below shows the number of bike trips by year showing the eight different bicycles types that are represented in the dataset. Notice that the question of bicycle type has only been included in the Danish National Travel Survey since 2014, hence years on the x-axis ranges from 2014-2021. It is obvious that the ordinary two wheel bike is by far the most dominant bicycle type. Zoom in on the remaining curves to see that E-bikes and Christiniabicycles are the second- and thirdmost popular types, respectively. The other  bike types have a very low number of counts in the range of 0-20 observations per year. 

{{< include-html "content/en/green/bike_type_part1.html" >}}

We're interested to see if there has been an increase in the use of bicycles and especially in the use of E-bikes. From the plot above it certainly looks like there has been a slight increase, but it cannot be stated with certainty from the absolute numbers. In the plot below, we solve this problem by looking at the percentage increase in the number of bike trips, ***x***, since 2014. Calculated for year ***i*** and bicycle type ***b***:

<div>$$\frac{x_{b,i} - x_{b,2014}}{x_{b,2014}} \cdot 100$$</div>

The use of Christianiabicycles has increased significantly (800%) from 2014 -2021! The E-bikes has also become more popular with 5-fold increase compared to the 2014 baseline. Interestingly, the ordinary two wheel bike retains its popularity, but it does not seem to be used more often. The same story goes for the remaining bicycle types.

{{< include-html "content/en/green/bike_type_part2.html" >}}

### Discussion and conclusion

Discussion. Think critically about your creation <br/>
What went well?<br/>
What is still missing? What could be improved? Why?

The dataset from the Danish National Transport Survey database contains much more data than what we have filtered out in this project. We have chosen to focus on bicycle trips, however, the dataset also contains trips by other modes of transport; car, public transport, a combination of those etc. Hence, there is potential for much further analysis. For example, one could investigate the trends in the use of different modes of transport and compare the development in bicycle habits in this perspective. Such analysis would give a more thorough to the answer we tried to answer above: Has there been an increase in the use of bicycles?
