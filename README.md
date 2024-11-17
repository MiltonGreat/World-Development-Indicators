# World Development Indicators

### Project Overview

This project analyzes socio-economic indicators from the World Bank Development Indicators dataset. The data provides insights into various metrics like GDP, life expectancy, literacy rates, trade, and renewable energy consumption across countries and regions over several decades. The goal is to extract meaningful insights using SQL, visualize trends, and save key results for further analysis.

#### Project Objectives

- SQL Query Practice: Use SQLite to perform complex queries, filtering, grouping, and aggregating data to answer key analytical questions.
- Visualization: Create insightful visualizations using Matplotlib and Seaborn to illustrate trends and comparisons.
- Data Cleaning: Handle missing values and inconsistent data for robust analysis.
- Save Results: Export results to CSV files for sharing and further analysis.

### Key Questions Answered

- Which countries have the highest GDP per capita?
- What is the trend in global life expectancy over the years?
- Which countries have the lowest access to electricity?
- How does GDP per capita correlate with life expectancy?
- Which regions have the highest renewable energy consumption?
- What are the trends in GDP growth globally?
- Which indicators have the most missing values?

### Dataset Description

The dataset is sourced from the World Bank and includes a variety of indicators for countries worldwide, spanning multiple years. The data is extracted from the file:

- Source File: P_Data_Extract_From_World_Development_Indicators_all_years_for_kaggle.xlsx
- Database File: world_development_indicators.db
  
Key dataset features:

- Country Name: Name of the country.
- Region: Regional grouping of countries.
- Time (Year): Year of the observation.
- Indicators: Metrics like GDP, population, literacy rate, life expectancy, trade percentage, etc.

### Project Workflow

Data Extraction:
- Extracted the data from the ZIP file into an Excel sheet.
- Loaded the data into a SQLite database for efficient querying.

Data Exploration:
- Inspected the dataset schema and sample data.
- Checked for missing values and inconsistencies.

SQL Queries:
- Performed analysis using SQL queries on various indicators, filtered by year, country, and region.

Visualization:
- Visualized GDP trends, life expectancy, and renewable energy consumption by region.

Save Results:
- Exported key outputs to CSV files for documentation and sharing.

### Notable Results

- Top 10 Countries by GDP Per Capita (2020): A list of the wealthiest countries by GDP per capita in 2020.
- Life Expectancy Trends: A year-wise trend of average life expectancy globally.
- Trade as a Percentage of GDP: Insights into which countries rely most on trade for their GDP.
- Access to Electricity: Identified countries with the lowest electricity access in 2020.

### Future Improvements

- Data Cleaning: Develop a pipeline to automate cleaning of missing and inconsistent data.
- Advanced Analytics: Include machine learning models to predict future trends.
- Interactive Visualizations: Build dashboards using tools like Tableau or Power BI.

### Source

https://www.kaggle.com/datasets/david780514/world-bank-world-development-indicators-1960-2023
