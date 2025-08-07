# Environmental-Analysis-of-Brazil-Weather
Repository dedicated to a project involving exploratory data analysis and data visualisation to analyse trends in Brazil's weather from the years 2001-2021 and using linear regression to create a rainfall forecasting tool which estimates the total monthly rainfall.

## Objective
Project objectives were to provide a report of the last two decades of weather change across Brazil and identify other countries with comparable weather characteristics.
In addition, identifying a list of areas in Brazil that would be suitable for harnessing wind power, for harnessing solar power and those which may require irrigation.
Finally, provide a tool to forecast the amount of rainfall in the future for an area that would be of interest to the local population.

## Methods
* Dataset aggregation:
As the data was over 10GB in size, making it difficult to process at once, each of the five regions' data was processed separately, to find averages of each environmental factor by month, day, hour and state. Each region's monthly, daily, hourly and state datasets were merged with the other regions data respectively. These four datasets were used for data exploration and visualisation using Tableau, the primary source of figures for the analysis report.

* Data visualisation:
Tableau was used to create graphs for the analysis report, focusing on general trends, as well as key factors contributing to wind and solar power generation, and conditions for irrigation. Additionally, exploratory data analysis was conducted using Python modules such as Seaborn and Matplotlib.

* Modelling:
For the rainfall forecast tool, Statsmodel's linear regression was used on monthly averages of one region's data to predict the total rainfall of a certain month. Model refinement included utilising scaling, and feature selection methods such as stepwise regression.

## Results
The results of the analysis can be found in the Analysis Report folder.

