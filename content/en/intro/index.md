---
title: "Introduction"
weight: 2
---

### About the data source

The data used in this project comes from the Danish National Travel Survey (Transportvaneundersøgelsen), which is a survey that aims to gather information on the transport behaviour of Danes residing in Denmark [1]. The survey is managed by DTU Transport on behalf of a group of Danish authorities and organisations. Here are some key points that describe the survey:

* It contains a one-day travel diary combined with various background questions
* Every day contains several trips with different modes of transport
* Covers 365 days a year
* Regards Danish residents, 10-84 years of age
* Interviews are performed from 2006-2021'

We will use two main datasets from the TU database. The **Session dataset** contains the background data about the person being interviewed, such as age, gender, home address, occupation etc. It contains:

**196006** one-day travel diaries in total

**139093** (71%) of participants owns a bike 🚲

The **Tur** dataset contains information on every trip in the one-day travel diary and includes details such as the time of departure and arrival, the mode of transport and the purpose of the trip. This dataset contains:

**575629** trips in total

**88688** (15%) bike trips 🚲


<img src="Number_of_interviews_per_year.png" width=800 height=600 />

In our analysis, we will use subsets of the dataset depending on the aim. In general, we focus on the trips where bicycle is the primary mode of transport. Furthermore, for some parts of the analysis we focus on the 15 top municipalities when it comes to total distance travelled. These are listed below

**Top 15 biking municipalities:**
1. København
2. Aarhus
3. Odense
4. Frederiksberg
5. Aalborg
6. Esbjerg
7. Gentofte
8. Gladsaxe
9. Silkeborg
10. Roskilde
11. Lyngby-Taarbæk
12. Herning
13. Viborg
14. Sønderborg
15. Vejle



{{< include-html "content/en/intro/intro_plot.html" >}}

### Design Space Dimensions

*Which genre of data story did you use?
Which tools did you use from each of the 3 categories of Visual Narrative (Figure 7 in Segal and Heer). Why?
Which tools did you use from each of the 3 categories of Narrative Structure (Figure 7 in Segal and Heer). Why?*

**Narrative genre**<br/>
We will make use of several genres of narrative visualization [2]. For example, a multi-view visualization (“partitioned poster”) to have a loose order to images, possibly combined with Flow Chart to suggest a path to the viewer. Time-series data can be displayed using Annotated Graphs within a Slide Show format allowing for interactivity through a timeline slider. Time-series data may also be presented in a video format.

**Visual Narrative**<br/>

**Narrative Structure**<br/>
For the oredering of the webiste content we have aimed for a user directed path with limited prescribed ordering of plots and a high degree of interactivity. The interactive components include hovering, selection and navigation buttons that allow the reader to create a customized view of the data. From the messaging tools, we have made use of captions and annotations to provide observations and explanations about the plots. 



References: 

[1] Danish National Travel Survey, [DOI: 10.11581/dtu:00000034](https://www.cta.man.dtu.dk/transportvaneundersoegelsen/dokumentation). Documentation: [Catalogue of variables]((https://www.tu2022.dk/meta/?lang=EN)).

[2] E. Segel and J. Heer, "Narrative Visualization: Telling Stories with Data," in IEEE Transactions on Visualization and Computer Graphics, vol. 16, no. 6, pp. 1139-1148, Nov.-Dec. 2010, doi: 10.1109/TVCG.2010.179.

