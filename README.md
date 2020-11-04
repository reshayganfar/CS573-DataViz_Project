# CS573 - Data Visualization Project

## Data

The data I visualized for my project is the WhoGov dataset provided by Nuffield College, University of Oxford [here](https://www.nuffield.ox.ac.uk/our-research/research-centres/nuffield-politics-research-centre/whogov/whogov-download-links/). The dataset contains information about more than 50,000 cabinet members from 177 countries, spanning July 1966 - July 2016. There is a separate entry for each cabinet member, from each country, for each year. Each entry contains information such as party affiliation, gender, age and military affiliation.

## Exploratory Visualizations

In the early phase of the project I created several exploratory visualizations in order to investigate the data. 

I’ve created five visualizations to investigate the data. Each of these visualizations is provided below with a brief description: 

[![image](https://user-images.githubusercontent.com/68825348/94755774-77f5e900-034a-11eb-9d5e-e123dd56edd7.png)](https://vizhub.com/reshayganfar/3452ae85ed284611b9f01ed085428735)

The above chart plots the ratio of female cabinet members against the ratio of military cabinet members. There are many data points along the x-axis (corresponding to a military ratio of zero) and many points along the y-axis (corresponding to a female ratio of zero). However, there appears to be a loosely correlated inverse relationship between the female ratio and the military ratio. This observation prompted me to want to dig deeper and investigate what other variables may be correlated with or possibly causing this relationship. 

[![image](https://user-images.githubusercontent.com/68825348/94756050-4af60600-034b-11eb-98c4-1fd69bb16c0b.png)](https://vizhub.com/reshayganfar/e72e753d5ff34c23bff7466351e5c12b)

The above chart was designed investigate the relationship between two other variables: (1) retention rate and (2) government type. While not a very strong indicator, the retention rate appeared to be lowest in presidential democracies (yellow bars), and highest in royal dictatorships (purple bars) and civilian dictatorships (blue bars). 

[![image](https://user-images.githubusercontent.com/68825348/95390738-b2133d80-08aa-11eb-891c-559aae692182.png)](https://vizhub.com/reshayganfar/f6bf28624809495f92feeafbe4b681cd)

The above chart plots the ratio of female cabinet members against the ratio of military cabinet members, color coded by region. Whereas the first plot displayed contained all data points for the entire 50-year span, this plot includes the average female and military ratio for each country over the last 15 years of the dataset. Several intersting points stood out in this chart. Africa has significant military presence in combination with female presence in government cabinets. Asia & Pacific and the Middle East have significant military presence with low female presence in government cabinets. Europe has the highest level of female involvement.

[![image](https://user-images.githubusercontent.com/68825348/98069025-acaa0400-1e12-11eb-8df0-276d8b49b2e7.png)](https://vizhub.com/reshayganfar/eeb9a18afdb04b79a81d38f7e7490aa9?mode=full)

The above chart plots the number of countries with a female ratio of zero over time. This plot shows that the number of countries was relatively static at about 100 until 1975, when the number started to decrease. Around 2006, the number stabilized at about 10 countries, until 2013 when the number began to slowly decrease again. 

## Final Visualization

[![image](https://user-images.githubusercontent.com/68825348/98069325-54273680-1e13-11eb-81a5-18693e57bd43.png)](https://vizhub.com/reshayganfar/ab6dbca1e3d84f8da96c3caf48b634cb?mode=full)

The final visualization for this WhoGove dataset is shown above. The chart is a scatterplot with the following features: 
* Tooltip: When hovering over a data point, the tooltip will provide the country name, x-value and y-value
* X- and Y-axis Dropdowns: The variable plotted on each access can be selected as any of the following three choices: (1) Female Ratio, (2) Military Ratio, and (3) Retention
* Color Dropdown: The meaning of the color coding can be changed between the following two options: (1) Region: color coding indicates the geographic region of each data point, and (2) Government system: color coding indicates the government system of each data point
* Color Legend: Hovering over keys on the color legend causes all other data series to fade out on the chart
* Slider: allows the user to select which year of data to view; year range from 1966 to 2016; tick marks indicate 10-year increments

Experimenting with the visualization settings allows the user to perceive the following: 
1) The female ratio increases over time
2) The military ratio decreases over time
3) African states stand out as having relatively high military ratios in combination with relatively high female ratios
4) Military dictatorships started out with a moderate military ratio, which increased through steadily into the 1980s (when military dictatorships had very high military ratios relative to other government systems) before decreasing to much lower levels again by 2016
5) No trend over time is apparent in the retention rate 

## Future Work

There are improvements that can be made to the existing visualization, as well as alternate visualizations that may be more effective with the given data set. 

#### Improvements to Existing Visualization

Test
