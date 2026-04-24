This project analyzes global COVID-19 data to identify trends in confirmed, recovered, and death cases across different countries. 
The analysis focuses on understanding the spread of the pandemic, comparing country-wise performance, and identifying key patterns over time using 
Python-based data analysis techniques.

Objectives


Analyze global COVID-19 trends over time
Compare confirmed, recovered, and death cases across countries
Identify peak infection periods and growth patterns
Calculate key metrics such as recovery and death rates
Visualize trends to derive meaningful insights




Dataset


Source: Public COVID-19 dataset (Johns Hopkins University / similar global dataset)
Data includes:
Confirmed cases
Death cases
Recovered cases
Country/Region and Province/State
Date-wise time series data



Tools & Technologies


Python
Pandas (Data Cleaning & Transformation)
NumPy
Matplotlib (Data Visualization)


Project Workflow


Data Loading
Imported multiple datasets for confirmed, deaths, and recovered cases
Data Cleaning
Handled missing values
Standardized column formats
Data Transformation
Converted data from wide format to long format using melt()
Merged datasets for unified analysis
Exploratory Data Analysis (EDA)
Grouped data by country and region using groupby()
Aggregated case counts for comparison
Visualization
Created line plots and bar charts to show trends over time
Compared multiple countries on key metrics



Key Insights


Certain countries experienced early spikes in infection rates compared to others
A steady increase in confirmed cases was observed globally over time
Recovery rates improved gradually in later stages of the pandemic
Significant variation exists in death and recovery rates across countries
