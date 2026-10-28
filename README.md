GOOGLE PLAY STORE EXPLORATORY DATA ANALYSIS


PROJECT OVERVIEW

This project performs an end to end Exploratory Data Analysis and data cleaning on the Google Play Store apps dataset. The main objective is to prepare raw data handle missing values and discover actionable insights regarding app ratings installations pricing strategies and category performance.


KEY OBJECTIVES

1. Category Analysis Identify which app categories have the highest market share and user installs.
2. Ratings and Reviews Study how user reviews and application size affect overall app ratings.
3. Free vs Paid Comparison Compare the download trends and user ratings of free apps versus paid apps.
4. Market Trends Find the key features of top performing applications with over one million installs.


TOOLS AND LIBRARIES USED

Programming Language Python
Data Manipulation Pandas and NumPy
Data Visualization Matplotlib and Seaborn
Spreadsheet Tools Microsoft Excel and Google Sheets
Development Environment Jupyter Notebook and Google Colab


DATA CLEANING AND PREPROCESSING WORKFLOW

1. Handling Missing Values Cleaned and imputed null records in the Rating Type Content Rating and Android Version columns.
2. Formatting Installs Column Removed text symbols from the Installs column and converted the data into numeric integer format.
3. Price Column Standardization Removed currency symbols from the Price column and converted values into numeric float format for revenue calculation.
4. Size Column Conversion Standardized the Size column by converting kilobytes and megabytes into a uniform megabyte scale.
5. Removing Duplicates Identified and removed duplicate app records to ensure accurate analysis.


KEY INSIGHTS FROM EDA

1. Top Categories Game Family and Tools categories have the highest number of listed apps while Communication and Social categories lead in average user installs.
2. Free vs Paid Distribution More than 92 percent of applications on the Google Play Store are free. Paid applications represent a smaller share but maintain strong ratings in niche categories like Medical and Personalization.
3. Rating Distribution The majority of apps have an average user rating between 4.1 and 4.4 out of 5 with a strong positive correlation between review count and total downloads.
4. Impact of App Size Lightweight applications under 30 megabytes show higher installation rates compared to heavy applications.


PROJECT FILES INCLUDED

1. raw playstore data csv Original dataset before cleaning
2. cleaned playstore data csv Processed and cleaned dataset used for analysis
3. playstore eda notebook ipynb Python notebook with complete data cleaning and visualization code
4. README md Project documentation and summary


HOW TO RUN THIS PROJECT

1. Download or clone this repository to your local system.
2. Open the Python notebook file in Jupyter Notebook or Google Colab.
3. Load the dataset and run all cells sequentially to view the data cleaning steps summary statistics and charts.


AUTHOR

Suresh Kumar Shah
Data Analytics and Business Intelligence Enthusiast
