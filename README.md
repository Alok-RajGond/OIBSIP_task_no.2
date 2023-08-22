# Unemployment-Analysis-In-India
This repository contains an analysis of unemployment in India from different regions during the years 2019 and 2020. The objective of this analysis is to understand the regional variations in unemployment rates and identify key insights for each region.

## Unemployment in India Analysis

This project focuses on analyzing unemployment in different regions of India for the years 2019 and 2020. The dataset contains information about the unemployment rate and other relevant variables for each region.

### Data Exploration and Preprocessing

- Checking the last 5 rows of the dataset using `df.tail()`.
- Checking the column names using `df.columns`.
- Determining the size of the dataset using `df.shape`.
- Checking the data types of all columns using `df.dtypes`.
- Converting the 'Date' column from object to datetime data type using `pd.to_datetime()`.
- Renaming the columns to remove extra spaces and improving readability.
- Exploring the dataset's statistical summary using `df.describe()`.
- Checking for missing values using `df.isnull().sum()`.
- Checking for duplicate records using `df[df.duplicated()]`.

### Exploratory Data Analysis

- Analyzing the distribution of records by area using a count plot and a pie chart.
- Analyzing the distribution of records by region using a count plot.
- Investigating the relationship between the estimated unemployment rate and region using a bar plot.
- Visualizing the estimated unemployment rate by region using a scatter plot.
- Dividing the date into separate columns for day, month, and year.
- Analyzing the estimated unemployment rate by year using a scatter plot with the y-axis range limited to 2018-2022.
- Creating an animated scatter plot to visualize the estimated unemployment rate by region and year using Plotly Express.

The analysis provides insights into the unemployment situation in different regions of India and allows for comparisons between years. The visualizations help in understanding the patterns and trends in unemployment rates across regions.

For more details, refer to the code and analysis in the Jupyter Notebook file.

Note: This description summarizes the analysis without including the code snippets. Please refer to the actual README.md file for the complete content, including the code snippets.
