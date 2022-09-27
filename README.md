# Data Visualization in Tableau - US Census Demographic Data

# Table of Contents

* [Introduction](#introduction)
* [About the Data Set](#about-the-data-set)
* [1. Diffusion of Ethinicities in the US](#1-diffusion-of-ethinicities-in-the-us)
* [2. Unemployment Insights for the US](#2-unemployment-insights-for-the-US)
* [3. ](#3-)


## <b>Introduction</b><br>

In this project I am exploring a US Census Demographic data set, and visualizing some findings using Tableau.


## <b>About the Data Set</b>

The data comes from [Kaggle](https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data), and it includes the census data for all US counties in 2015. The data originates from the DP03 and DP05 tables of the 2015 American Community Survey 5-year estimates, while the Census Bureau updates the estimates approximately every year. 

For this project, I am using the data file _acs2015countydata.csv_, which provides data for each US county, including DC and Puerto Rico.
For the full data sets and more information, please refer to the [United States Cencus Bureau website](https://data.census.gov/cedsci/).

___________________

## [1. Diffusion of Ethinicities in the US](https://public.tableau.com/app/profile/dimitra.karamperi/viz/DiffusionofEthnicitiesintheUS/Sheet1)

![Diffusion of Ethinicities in the US](https://github.com/dimikara/US-Census-Demographic-Data/blob/main/img/Diffusion%20of%20Ethinicities%20in%20the%20US.png)


### Link

You may find the Worksheet [here](https://public.tableau.com/app/profile/dimitra.karamperi/viz/DiffusionofEthnicitiesintheUS/Sheet1)


### Summary

In this visualization, we can see all the ethnicities for which there is data for in the provided data set:

- **Asian**
- **Black**
- **Hispanic**
- **Native**
- **White**

appearing in alphabetical order.

We can see is that the more evenly distributed ethnicities are the White & Asian populations. To further explain, by even distribution, I mean that these two ethinicities seem to appear more evenly in most states. In contrast, the black community for example seems to exist mostly in 9 states (9 peaks), while the Latino community seems to be living in mostly 2 states, Puerto Rico & Texas, which correspond to the two prominent peaks. Lastly, the Native community is somewhere in the middle, showing 6-7 peaks, but with the lowest population numbers.


### Design

I chose the area chart as it is visually the most appropriate to illustrate the above finding. It is a simple but effective choice that reveals something that might not be so intuitive to understand otherwise.

I added two filters, to facilitate the filtering based on state & county, in case the reader wants to get the appropriate info in a more in depth level. Upon selecting a state, we can also see the actual data for all ethinicities for the given state.



### Resources

N/A

___________________

## [2. Unemployment Insights for the US](https://public.tableau.com/app/profile/dimitra.karamperi/viz/UnemploymentInsightsfortheUS/UnemploymentInsights)

![Unemployment Insights for the US](https://github.com/dimikara/US-Census-Demographic-Data/blob/main/img/Unemployment%20Insights%20for%20the%20US.png)

### Link

You may find the Dashboard [here](https://public.tableau.com/app/profile/dimitra.karamperi/viz/UnemploymentInsightsfortheUS/UnemploymentInsights)

### Summary

In this visualization, we can see some insights about the unemployment in the US. I am focusing on the top 10 states with the highest unemployment values. In a descending order, these states are:
- Texas
- Georgia
- Puerto Rico
- Kentucky
- North Carolina
- Mississipi
- Virginia
- Tennessee
- Missouri
- Michigan

The first obvious finding is that all these 10 states are in the eastern part of the US, with most of them being in the south as only Michigan lies on the north.

Not so surprisingly, we can see that Unemployment and Poverty usually go hand by hand. This is represented by the visualization on the top right. In the tooltip, I chose to also include the data for Child Poverty as an extra interesting piece of information. As we can see by the blue color differences, Child Poverty follows more or less the same pattern with Poverty, with the exception of Missouri that has higher than expected values for both Poverty and Child Poverty.

The last part of the Dashboard, on the bottom right, has a two-fold role: the first one is to give us some more extra arithmetic data about the 10 countries that we examine, as an attempt to expand our understanding of the relationship between Unemployment, Income per Capita, and Population. At the same time, the visualization gives a quick sense of the size of Poverty as the bar appears as thick or thin.


### Design

I made use of the map that can be embedded in a Tableau worksheet in order to see how the top 10 states with the highest unemployment are spread geographically. 

In the map, the Highlight State bar is used for an easy navigation: upon choosing a state out of the 10 that are available, the data is automatically highlighted in the visualization parts on the right. We may also click on a state in a table on the right, and get directly the data on the map and on the other table/graph, as both tables act as a filter. 

For comparing Unemployment and Poverty, I actually took my inspiration from the popular population pyramid charts. I have also added the data for Child Poverty, using hues of blue as a differentiator in order to give a prompt sense of the metric: the darkest the blue color is, the highest the Child Poverty is.

In the last part of the Dashboard, I am giving mainly some arithmetic data along with the dimension of Poverty represented by the thickness of the bars: the more thick the line is the higest the poverty is, and the opposite.

Finally, I chose the combination of blue & orange for the visualizations as it is the suggested combination for people with color blindness issues.


### Resources

* [How to Create a Population Pyramid Chart in Tableau](https://www.doingdata.org/blog/how-to-create-a-population-pyramid-chart-in-tableau)
* [5 tips on designing colorblind-friendly visualizations](https://www.tableau.com/about/blog/examining-data-viz-rules-dont-use-red-green-together)

___________________

## [Visualization #3]()

### Link

### Summary

A brief description of the visualization and the main story or findings conveyed


### Design

Explain any design choices you made including changes to the visualization after collecting feedback

As bar charts are great to visually compare differences, I am using 


### Resources

List of Web sites, books, forums, blog posts, GitHub repositories, etc that you referred to or used in this submission (Add N/A if you did not use such resources).
