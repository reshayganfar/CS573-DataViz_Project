# CS573 - Data Visualization Project

## Data

The data I propose to visualize for my project is the WhoGov dataset provided by Nuffield College, University of Oxford [here](https://www.nuffield.ox.ac.uk/our-research/research-centres/nuffield-politics-research-centre/whogov/whogov-download-links/). The dataset contains information about more than 50,000 cabinet members from 177 countries, spanning July 1966 - July 2016. There is a separate entry for each cabinet member, from each country, for each year. Each entry contains information such as party affiliation, gender, age and military affiliation.

## Prototypes

I’ve created four visualizations to investigate the data. Each of these visualizations is provided below with a brief description: 


[![image](https://user-images.githubusercontent.com/68825348/94755774-77f5e900-034a-11eb-9d5e-e123dd56edd7.png)](https://vizhub.com/reshayganfar/3452ae85ed284611b9f01ed085428735)

The above chart plots the ratio of female cabinet members against the ratio of male cabinet members. In general there appears to be an inverse relationship between the two.

[![image](https://user-images.githubusercontent.com/68825348/94755896-dd49da00-034a-11eb-90e1-491aa9a776e6.png)](https://vizhub.com/reshayganfar/9cd83f48e9464b69823f5d603b4088c4)

The above chart plots the ratio of female cabinet members over time; the ratio of female cabinet members appears to be increasing over time.

[![image](https://user-images.githubusercontent.com/68825348/94756050-4af60600-034b-11eb-98c4-1fd69bb16c0b.png)](https://vizhub.com/reshayganfar/e72e753d5ff34c23bff7466351e5c12b)

The chart was designed to investigate the question "How does retention rate vary across different governmental systems?" Based on the chart, it appears as though Civilian Dictatorships and Royal Dictatorships have the highest average retention rates while Mixed Democratic, Parliamentary Democracy and Presidential Democracy have lower average retention rates.

[![image](https://user-images.githubusercontent.com/68825348/94756819-67933d80-034d-11eb-8f7d-3bb68f8bc823.png)](https://vizhub.com/reshayganfar/14699b46c9104e9492b0fe0af3df991e)

The chart was designed to investigate the question "How does the ratio of females in cabinets different governmental systems?" Based on the chart, it appears as though Mixed Democratic, Parliamentary Democracies and Presidential Democracies have slightly higher ratios of females in cabinets while it appears that Military Dictatorships and Royal Dictatorships have lower ratios.

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How does government type impact the ratio of females in the cabinet? Ratio of military? Retention? The prototype visualizations above have started this investigation. 
 * How does the ratio of females in cabinets change over time? How is it impacted by government type? Is it correlated with military involvement or retention rate? These questions can be investigated with a dynamic bubble chart (refer to Sketch section below). 
 * How does region impact retention rates? Female ratio in the cabinet? These can be investigated using bar charts similar to those already plotted, using region for color coding instead of governmental system. These can also be investigated in a bubble chart. 
 * The bar charts and bubble plots outlined above could be made interactive by allowing the user to change variables, or to make the graphs dynamic over time using a slider. 

## Sketches

(insert one or more hand-drawn sketches of interactive visualizations that you imagine)
(describe each sketch - how is the data visualized, what are the interactions, and how do these relate to the questions/tasks)

## Open Questions

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)
