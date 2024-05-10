# Datafied_Database-Management-of-a-Car-Sharing-Company

**Documentation Outline**
---

-[Project Overview](#project-overview)

-[Data Source](#data-source)

-[Tools Used](#tools-used)

-[Data Cleaning and Preparation](#data-cleaning-and-preparation)

-[Database Management](#database-management)

-[SQL Queries and Findings](#sql-queries-and-findings)

-[Conclusion](#conclusion)

-[Glossary](#glossary)

# Project Overview
---

This project involved a dataset containing data on the prices of different brands and models of smartwatches available in the market. The datasets give information about the smartwatches' specifications and how they affect the market price. This data analysis project aims to explore the various specifications of wristwatch brands and look at the more suitable brands in terms of functionality, health specifications, and cost-efficiency for buyers.

# Data Sources
---
This data was provided by Datafied [https://www.kaggle.com/datasets/rkiattisak/smart-watch-prices]

# Tools Used
--- 
Microsoft Excel - for primarily housing the data,
Power Query Editor in Excel
SQLite. to install SQLite [https://www.sqlite.org/download.html]
Windows Command Prompt as a command-line interface

# Data Cleaning and Manipulation
---
Cleaning and transformation of the data were performed in the Power BI query which included the following:

1. Changing of data types
2. Splitting of columns
3. Creating conditional columns to create more measures
4. Removing empty and duplicate rows
5. Removing N/As
7. Made sure the values are consistent within the column for better visualization

# Exploratory Data Analysis
---

The data set contains 371 different smartwatch models with different specifications that influence the price of the smartwatches. The following are the insights to be derived from the analysis:

1.	Total number of smartwatches in the dataset
2.	Total number of smartwatch brands in the dataset
3.	Maximum battery life of smartwatches in the dataset

# Glossary

id: This column likely stands for the unique identifier of each record or entry in the dataset. It's a common practice to have an ID column in databases to uniquely identify each row.
timestamp: This column typically represents the date and time when a particular event or observation occurred. It's a timestamp indicating when the data was recorded.
season: This column likely denotes the season of the year when the data was recorded, such as winter, spring, summer, or autumn/fall.
holiday: This column may indicate whether the day when the data was recorded was a holiday or not. It could be a binary indicator where 1 represents a holiday and 0 represents a non-holiday.
workingday: This column might indicate whether the day when the data was recorded was a working day or not. Similar to "holiday," it could be a binary indicator.
humidity: This column probably represents the humidity level at the time when the data was recorded. Humidity is a measure of the amount of moisture present in the air.
windspeed: This column likely represents the speed of the wind at the time when the data was recorded. It indicates how fast the wind is blowing.
demand: This column might represent the demand for car-sharing services at the time when the data was recorded. It could indicate the number of rides or bookings made during a specific period.
weekday name: This column probably represents the name of the weekday corresponding to the date when the data was recorded.
month name: This column likely represents the name of the month corresponding to the date when the data was recorded.
hour: This column may represent the hour of the day when the data was recorded. It indicates the specific time within a day.
weather: This column likely represents the weather conditions at the time when the data was recorded. It could include descriptions such as clear, cloudy, rainy, snowy, etc.
weather_code: This column may represent a numerical code corresponding to the weather conditions described in the "weather" column. It could be used for classification or encoding purposes.
temp: This column probably represents the temperature at the time when the data was recorded, measured in degrees Celsius or Fahrenheit.
temp_feel: This column might represent the perceived or "feels-like" temperature, which can be influenced by factors such as humidity and wind speed.
temp_category: This column could represent a categorical classification of the temperature into groups such as cold, mild, or hot, based on predefined thresholds.





