# CS573 - Data Visualization Project

## Data

The data I visualized for my project is the WhoGov dataset provided by Nuffield College, University of Oxford [here](https://www.nuffield.ox.ac.uk/our-research/research-centres/nuffield-politics-research-centre/whogov/whogov-download-links/). The dataset contains information about more than 50,000 cabinet members from 177 countries, spanning July 1966 - July 2016. There is a separate entry for each cabinet member, from each country, for each year. Each entry contains information such as party affiliation, gender, age and military affiliation.

## Exploratory Visualizations

In the early phase of the project I created several exploratory visualizations in order to investigate the data. 

I’ve created five visualizations to investigate the data. Each of these visualizations is provided below with a brief description: 

[![image](https://user-images.githubusercontent.com/68825348/94755774-77f5e900-034a-11eb-9d5e-e123dd56edd7.png)](https://vizhub.com/reshayganfar/3452ae85ed284611b9f01ed085428735)

The above chart plots the ratio of female cabinet members against the ratio of male cabinet members. There are many data points along the x-axis (corresponding to a military ratio of zero) and many points along the y-axis (corresponding to a female ratio of zero). However, there appears to be a loosely correlated inverse relationship between the female ratio and the military ratio. This observation prompted me to want to dig deeper and investigate what other variables may be correlated with or possibly causing this relationship. 

[![image](https://user-images.githubusercontent.com/68825348/94755896-dd49da00-034a-11eb-90e1-491aa9a776e6.png)](https://vizhub.com/reshayganfar/9cd83f48e9464b69823f5d603b4088c4)

The above chart plots the ratio of female cabinet members over time; the ratio of female cabinet members appears to be increasing over time.

[![image](https://user-images.githubusercontent.com/68825348/94756050-4af60600-034b-11eb-98c4-1fd69bb16c0b.png)](https://vizhub.com/reshayganfar/e72e753d5ff34c23bff7466351e5c12b)

The chart was designed to investigate the question "How does retention rate vary across different governmental systems?" Based on the chart, it appears as though Civilian Dictatorships and Royal Dictatorships have the highest average retention rates while Mixed Democratic, Parliamentary Democracy and Presidential Democracy have lower average retention rates.

[![image](https://user-images.githubusercontent.com/68825348/94756819-67933d80-034d-11eb-8f7d-3bb68f8bc823.png)](https://vizhub.com/reshayganfar/14699b46c9104e9492b0fe0af3df991e)

The chart was designed to investigate the question "How does the ratio of females in cabinets different governmental systems?" Based on the chart, it appears as though Mixed Democratic, Parliamentary Democracies and Presidential Democracies have slightly higher ratios of females in cabinets while it appears that Military Dictatorships and Royal Dictatorships have lower ratios.

[![image](https://user-images.githubusercontent.com/68825348/95390738-b2133d80-08aa-11eb-891c-559aae692182.png)](https://vizhub.com/reshayganfar/f6bf28624809495f92feeafbe4b681cd)

The chart was designed to investigate the question "How does the ratio of females in cabinets relate to the ratio of military personal in cabinets in different regions?" Africa stands out as a region that has significant military presence in combination with female presence in government cabinets. Asia & Pacific and the Middle East stand out as having significant military presence with low female presence in government cabinets. Europe stands out as having the highest level of female involvement.

## Sketch

The sketch below shows an interactive bubble chart that can be used to observe patterns over time in the data. This sketch will also include the interactions listed in Items 1-3 in the previous section. 

![image](https://user-images.githubusercontent.com/68825348/94760479-7979de00-0357-11eb-9235-ed0768c9e617.png)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How does government type impact the ratio of females in the cabinet? Ratio of military? Retention? The prototype visualizations above have started this investigation. 
 * How does the ratio of females in cabinets change over time? How is it impacted by government type? Is it correlated with military involvement or retention rate? These questions can be investigated with a dynamic bubble chart (refer to Sketch section below). 
 * How does region impact retention rates? Female ratio in the cabinet? These can also be investigated in the bubble chart above, using the color to indicate region. 

## Interaction in the Vizualization

There are four types of interaction that I want to add to the visualization: 
1) Tooltip: When the mouse hovers over a data point, the country name, x-variable value and y-variable value will be displayed. 
2) X- and Y-Variable Menus: There will be a dropdown to select the variable on each axis; the two dropdowns will contain the same options. Options will include: size of cabinet, female ratio, military ratio and retention rate.
3) Color Menu: There will be a dropdown menu to allow the user to change the color coding. The two options will be geographic region and government system. 
4) Slider for Year: As mentioned above, the dataset covers a 50-year span (1966 - 2016). A slider will be introduced to allow the user to select which year of data to display. 

## Schedule of Deliverables
Below is the list of tasks that I will complete for this project: 
* Clean and format data for final deliverable - 10/14/20
* Create base scatter plot using single year of data - 10/21/20
- Add x- and y-axis menus - 10/21/20
- Add color menu - 10/21/20
- Add tooltip displaying country name and x- & y-axis values - 10/28/20
* Add slider to allow user to adjust the year of data being used - 11/04/20

## Open Questions

I am fairly concerned about my ability to implement a dynamic bubble chart in D3 and React. My programming background is limited (I have done some work in RStudio and implemented a RShiny app prior to this course). I am largely patching things together in this course. I am trying to learn JavaScript and to fully understand each topic mentioned in the lectures, but it has been fast-paced and is difficult for me. I will continue trying to learn the required skills and will begin re-watching lectures to hopefully gain a deeper understanding prior to attempting this visualization. 
