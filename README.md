# Data Visualization in Tableau - US Census Demographic Data

## <b>Introduction</b><br>

This data comes from a Kaggle dataset, it includes the census data for all counties in 2015. You can find the dataset in supporting materials at the bottom of this page. Required dashboards

You are required to create three visualizations. Some questions you may attempt to answer include those pertaining to the following areas:

Which states have the best transportation?

This is a fairly subjective question, so your first job is to define what the best transportation is. Is it highest percentage of transit use? Is it lowest mean commute times. Then you need to determine how to aggregate the data from the county level to the state. Are there outlier counties affecting the data? How should you aggregate all the data from the counties to represent the state effectively? Please provide your reasoning in your report.

How does income and poverty look across America?

Think about how best to contrast this data to show an interesting finding. You can look across many of the different fields to show interesting findings. Do counties with more construction experience more or less poverty? Do counties near the coast experiene more or less income? Remember this is all correlation and not causation so we cannot say any one thing causes it but we can report descriptive statistics.

You can also come up with your own question!

As you work with the data, come up with a question you're curious about and can be answered from the data. Build a dashboard or story to answer your question and lead viewers to that answer.

## Kaggle

About Dataset
Context
This dataset expands on my earlier New York City Census Data dataset. It includes data from the entire country instead of just New York City. The expanded data will allow for much more interesting analyses and will also be much more useful at supporting other data sets.

Content
The data here are taken from the DP03 and DP05 tables of the 2015 American Community Survey 5-year estimates. The full datasets and much more can be found at the American Factfinder website. Currently, I include two data files:

acs2015censustract_data.csv: Data for each census tract in the US, including DC and Puerto Rico.
acs2015countydata.csv: Data for each county or county equivalent in the US, including DC and Puerto Rico.
The two files have the same structure, with just a small difference in the name of the id column. Counties are political subdivisions, and the boundaries of some have been set for centuries. Census tracts, however, are defined by the census bureau and will have a much more consistent size. A typical census tract has around 5000 or so residents.

The Census Bureau updates the estimates approximately every year. At least some of the 2016 data is already available, so I will likely update this in the near future.

Acknowledgements
The data here were collected by the US Census Bureau. As a product of the US federal government, this is not subject to copyright within the US.

Inspiration
There are many questions that we could try to answer with the data here. Can we predict things such as the state (classification) or household income (regression)? What kinds of clusters can we find in the data? What other datasets can be improved by the addition of census data?


## Questions to Ask

