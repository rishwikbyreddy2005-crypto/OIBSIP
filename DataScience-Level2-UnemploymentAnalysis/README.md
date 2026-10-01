# Unemployment Analysis with Python

## 📌 Project Overview

This project is part of the **OASIS Infobyte Data Science Internship – Task 2**.

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on unemployment data in India to identify regional and temporal trends, with a focus on the impact of the COVID-19 pandemic on unemployment rates.

---

## 🎯 Objectives

- Load and inspect the unemployment dataset.
- Check the dataset shape, data types, and missing values.
- Analyze the average unemployment rate by region.
- Study monthly unemployment trends.
- Visualize unemployment rates over time for selected regions.
- Identify the top 10 regions with the highest average unemployment rate.
- Analyze correlations between unemployment, employment, and labour participation rates.
- Compare pre-COVID and post-COVID unemployment indicators.
- Derive meaningful observations from the visualizations.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains unemployment-related information for different regions of India.

### Features

- `Region`
- `Date`
- `Frequency`
- `Estimated Unemployment Rate (%)`
- `Estimated Employed`
- `Estimated Labour Participation Rate (%)`

The dataset used in this analysis contains **1,822 rows and 6 columns**.

---

## 🔍 Exploratory Data Analysis

### 1. Dataset Inspection

The dataset was loaded and inspected to understand:

- Number of rows and columns
- Column names
- Data types
- Missing values
- First few records

### 2. Region-wise Average Unemployment

The average unemployment rate was calculated for each region to identify regional differences in unemployment.

### 3. Monthly Unemployment Trends

Monthly average unemployment rates were calculated and visualized using a line chart to identify changes over time.

### 4. Regional Time-Series Analysis

Unemployment rates were visualized over time for:

- Andhra Pradesh
- Karnataka
- Tamil Nadu

This helps identify regional fluctuations and changes during the study period.

### 5. Top 10 Regions with Highest Average Unemployment

A bar chart was created to identify the top 10 regions with the highest average unemployment rates.

### 6. Correlation Analysis

A correlation heatmap was created to analyze relationships between:

- Estimated Unemployment Rate
- Estimated Employed
- Estimated Labour Participation Rate

### 7. Pre-COVID vs Post-COVID Analysis

The dataset was divided into pre-COVID and post-COVID periods, and the average unemployment rate and labour participation rate were compared.

---

## 📈 Visualizations

The project includes the following visualizations:

1. Dataset Preview
2. Dataset Information
3. Average Unemployment Rate by Region
4. Monthly Average Unemployment Rate
5. Unemployment Rate Over Time
6. Top 10 Regions with Highest Average Unemployment Rate
7. Correlation Heatmap
8. Pre-COVID vs Post-COVID Comparison

---

## 💡 Key Observations

- Unemployment rates vary across different regions of India.
- Monthly unemployment rates show fluctuations throughout the study period.
- A significant increase in unemployment can be observed around the COVID-19 period.
- Andhra Pradesh, Karnataka, and Tamil Nadu show different unemployment patterns over time.
- The top-10 analysis identifies regions with relatively higher average unemployment rates.
- The correlation heatmap shows the relationships between the selected employment indicators.
- The pre-COVID and post-COVID comparison shows changes in unemployment and labour participation rates.

---

## 📁 Project Structure

```text
OIBSIP/
│
└── DataScience-Task-2-Unemployment-Analysis/
    │
    ├── Unemployment_Analysis.ipynb
    ├── README.md
    ├── dataset.csv
    │
    └── screenshots/
        ├── dataset_preview.png
        ├── dataset_info.png
        ├── average_unemployment_by_region.png
        ├── monthly_unemployment_trend.png
        ├── unemployment_over_time.png
        ├── top_10_regions.png
        ├── correlation_heatmap.png
        └── pre_covid_vs_post_covid.png
