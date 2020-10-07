# COVID-19-Data-Analysis

# Libraries
###### 
· Covid- Python package to get information regarding the novel corona virus provided by Johns Hopkins university and worldometers.info
###### 
· Matplotlib- Python packages used for data visualization.
###### 
· NumPy- Python library used to maintain the data in the matrices format.
###### 
· Pandas- It is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

# Data Visulization
######
Data of covid is imported from the JHU reporistory.
######
It diplays the following data for overall and for particular country:
######
1) Total confrimed cases
######
2) Total active cases
######
3) Total death cases
######
4) Total recovered cases

# Graph Analysis
######
1)Loaded global data from JHU repository
Imported the csv file of confirmed and active cases in order to abstract the data for the graph using the following link:
######
confirmed = ‘https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv'
######
active = ‘https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_active_global.csv'
###### 
2) Declared function covidData to extract data for specific countries
Here the function covidData is defined as:
def covidData(country, output=1, start=100):
where,
Country- string representing country which you want get the data in graph.
Output — type of output desired
State — return data starting at the nth case, represented by the value of default 100.
###### 
3) Generate plot parameters
Here the font, axis, tick and link properties are declared.
###### 
4)Plot confirmed cases — starting at 1000th case
In this graph the starting point is considered as (x, y)=(0,1000). The axis are scale to logarithmic. The range of the plot is set to x-axis=280(days) and y-axis=10,000,000(cases).
###### 
5)Plot active cases — starting at 100th case
In this graph the starting point is considered as (x, y)=(0,100). The axis are scale to logarithmic. The range of the plot is set to x-axis=280(days) and y-axis=1,000,000(cases).

