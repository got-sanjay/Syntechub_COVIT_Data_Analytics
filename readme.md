# COVID-19 Data Analytics

A simple project that analyzes global COVID-19 time-series data using Python.  
It includes daily/weekly case computation, rolling averages, peak detection,  
and basic reproduction (R-like) insight.

## Project Features

### Data Processing
- Load COVID-19 global time-series
- Convert cumulative data => daily new cases
- Smooth noise using 7-day rolling averages

### Visual Analysis
- Country comparison plots
- Peak detection using prominence-based peak finding
- R-value growth insight (weekly growth ratio)

## Requirements

Install all dependencies:
`pip install -r requirements.txt`

## Dataset Source

COVID-19 Global confirmed Dataset (Time Series):  
[Dataset Link](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

## charts
| Dashboard View | Manage Books | Issue/Return |
|----------------|--------------|--------------|
| ![Week Avg](src/charts/Country%20Comparison%20weekly%20Average.png) | ![Peaks](src/charts/COVID-19%20Peaks%20India.png) | ![R Insights](src/charts/Basic%20Reproduction%20Insight.png) |


## Author
[Sanjay Kumar](https://got-sanjay.github.io/portfolio/) \
Data Science & Deep Learning Developer \
[LinkedIn](https://www.linkedin.com/in/gotsanjay)
 | [GitHub](https://github.com/got-sanjay)

