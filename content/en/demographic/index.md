---
title: "Demographic analysis"
weight: 5
---

### Demographic analysis of the top 15 bike municipalities

Only looking at the 15 mostly biking municipalities in Denmark there is a close to equal distribution between male and female cyclists. There are 19700 female and 17156 male, hence the women/girls are overrepresented by 15% compared to the men/boys. The population pyramid below illustrates the age distribution for both genders. Surprisingly, the ten to fifteen year olds either constitute a big part of the trip dataset or they bike relatively more often than the other age groups.

<img src="gender_dist.png" width=800 height=600 />

Every cyclist in the transport survey bikes 2.56 trips per day on average. The bike is mostly used for travelling short distances around 2-4 km. Hence, people use the bike to go around in their close surroundings, but what is their purpose at the destination? Work? Education? Shopping? Luckily, the dataset includes this information, so we can investigate it through an interactive plot! The purpose of the bike trip is defined as the purpose at the destination that is opposite home. Hence, if a trip consists of *going home* from work, the purpose will still be Workplace. The Education category is going to/from school or another educational institution. Errand includes several activities, such as collecting/bringing others or going shopping. The Leisure category covers youth clubs, day care, church, visiting family or going to do sports. Lastly, Business describes purposes such as conferences, customer visits and other commercial transport.

This Bokeh plot below let's you investigate the bike trip purpose for people in different age groups across the 24 hours of day. You can read some of our conslucions underneath the plot, but we encourage you to do some exploration on your own at first!

{{< include-html "content/en/demographic/demographic_plot.html" >}}

**Age 5-19:** The youngest age group bikes to school in the morning between 7-8am and home again early in the afternoon at around 1-3pm. In the afternoon and evening hours, Leisure is their primary bike trip purpose, hence they bike to some sort of sparetime activity. People in this age group run very few errands and the Business category is also negligible.
**Age 20-39:** From 20-39 years of age, the Educational purpose is almost entirely replaced by Workplace. Hence, people at this age have finished school and now bike to and from work instead. The day is a couple of hours longer for the 20-39 year olds than for the youngest age group and they go home from work at 3-5pm. Errand make out a large part of the bike trip purposes in the afternoon, but there is still time to leisure activities as well.
**Age 40-59:** The bike habits for this age group are similar to those of people who are 20 years younger. They go to and from work at roughly the same times and spend the afternoon running errands an doing freetime activities. The Business purposes are uniformly distributed throughout the day, however, there is a decent number of business activities happening at midnight. Wonder what these could be 🤔...
**Age 60-90:** At this age, only a few people still go to work so they have the time to run errands and to leisurely activities during the day between 9am and 4pm. Interestingly, the Errand category make out a majority of the bike trips at noon, which could be due to the fact that retirees like to get their shopping done between 10-12am when the stores aren't so crowded. 
