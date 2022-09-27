# Data Visualization in Tableau - US Census Demographic Data

# Table of Contents

* [Introduction](#introduction)
* [About the Data Set](#about-the-data-set)
* [Distribution of Ethinicities in All US States](#distribution-of-ethinicities-in-all-us-states)
* [Unemployment Insights for the US](#unemployment-insights-for-the-US)


## <b>Introduction</b><br>

In this project I am exploring a US Census Demographic data set, and visualizing some findings using Tableau.


## <b>About the Data Set</b>

The data comes from [Kaggle](https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data), and it includes the census data for all US counties in 2015. The data originates from the DP03 and DP05 tables of the 2015 American Community Survey 5-year estimates, while the Census Bureau updates the estimates approximately every year. 

For this project, I am using the data file _acs2015countydata.csv_, which provides data for each US county, including DC and Puerto Rico.
For the full data sets and more information, please refer to the [United States Cencus Bureau website](https://data.census.gov/cedsci/).

___________________

## [Distribution of Ethinicities in All US States](https://public.tableau.com/app/profile/dimitra.karamperi/viz/DistributionofEthinicitiesinAllUSStates/Sheet1)

### Link

https://public.tableau.com/app/profile/dimitra.karamperi/viz/DistributionofEthinicitiesinAllUSStates/Sheet1

![Distribution of Ethinicities in All US States](https://user-images.githubusercontent.com/8607482/192156346-4be8cff7-4d1a-455b-ad6e-db1d0fbab4d7.png)


### Summary

In this visualization, we can see all the ethnicities for which there is data for in the provided data set, i.e. **Asian**, **Black**, **Hispanic**, **Native**, and **White**, in alphabetical order.

We can see is that the more evenly distributed ethnicities are the White & Asian populations. To further explain, by even distribution, I mean that these two ethinicities appear in many states 


### Design

I chose this bar chart as the most appropriate, in my opinion, for illustrating the above finding. It is a simple but effective choice that reveals something that may not be so intuitive to understand otherwise.

I added two filters, to facilitate the filtering based on state & county, if the reader wants to get the appropriate info in a more in depth level. I have also added data labels following the Min/Max option, so that it is easy to see the highest and lowest value for each ethinicity.



### Resources

* [How to Visualize Likert Scale Data in Tableau](https://www.rigordatasolutions.com/post/how-to-visualize-likert-scale-data-in-tableau)

___________________

## [Unemployment Insights for the US](https://public.tableau.com/app/profile/dimitra.karamperi/viz/UnemploymentInsightsfortheUS/UnemploymentInsights)
![Unemployment Insights for the US](https://github.com/dimikara/US-Census-Demographic-Data/blob/main/img/Dashboard%202.png)

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

In the map, the Highlight State bar is used for an easy navigation: upon choosing a state out of the 10 that are available, the data is automatically highlighted in the visualization parts on the right.

Not so surprisingly, we can also see that Unemployment and Poverty usually go hand by hand. This is represented by the visualization on the top right. In the tooltip, I chose to also include the data for Child Poverty as an extra interesting piece of information. As we can see by the blue color differences, Child Poverty follows more or less the same pattern with Poverty, with the exception of Missouri that has higher than expected values for both Poverty and Child Poverty.

The last part of the Dashboard, on the bottom right, has a two-fold role: the first one is to give us some more extra arithmetic data about the 10 countries that we examine, as an attempt to expand our understanding of the relationship between Unemployment, Income per Capita, and Population. At the same time, the visualization gives a quick sense of the size of Poverty as the bar appears as thick or thin.


### Design

I made use of the map that can be embedded in a Tableau worksheet in order to see how the top 10 states with the highest unemployment are spread geographically. 

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
