# 🚗 Uber Trip Data Analysis: From Cleaning to EDA

📘 Overview

This project analyzes an Uber trip dataset, focusing on cleaning, feature engineering, and exploratory data analysis (EDA). The goal is to uncover insights into trip duration, distance, temporal patterns, and travel purposes.

# 📂 Dataset

The dataset contains key information such as start and end dates, start/stop locations, miles traveled, trip category, and purpose. After initial inspection, data cleaning and feature engineering steps were performed to make the data suitable for analysis.

# 🛠️ Data Cleaning

Date Conversion: START_DATE and END_DATE converted to datetime format.

Invalid Rows: Removed rows with null dates (e.g., summary rows like "Totals").

Duplicates & Missing Values: Dropped duplicate rows and filled missing PURPOSE values with 'Unknown'.

# ✨ Feature Engineering

Trip Duration: ⏱️ Calculated as the difference between END_DATE and START_DATE (in minutes).

Day of the Week: 📅 Extracted from START_DATE.

Hour of Day: ⏰ Extracted from START_DATE.

# 📊 Exploratory Data Analysis (EDA)

## 📈 Trip Duration & Distance

Trip Duration Distribution: Most trips last between 10–30 minutes, with some longer outliers.

Trip Distance Distribution: Most trips are under 20 miles, though a few extend over 300 miles.

## ⏳ Temporal Patterns

Trips by Day of Week: 🗓️ Highest activity on weekdays, especially Wednesday and Thursday, indicating work-related travel.

Trips by Hour of Day: ⌛ Clear peaks during morning (7–9 AM) and evening (4–6 PM) commute hours, with a smaller lunchtime peak.

## 🏁 Purpose & Category

Trips by Purpose: 🧑‍💼 Most common purposes are meetings and customer visits, emphasizing a business-oriented dataset.

Trips by Category: 📊 Predominantly business trips, with very few personal trips.

# 📉 Visualizations

The analysis includes various plots to illustrate key findings:

### 📊 Histograms for trip duration and distance.

### 📈 Count plots for trips by day, hour, purpose, and category.

# ✅ Conclusion

The data reveals strong business travel patterns, with most trips occurring during weekdays and commute hours for meetings and customer visits. 
