# Car Price Prediction with Machine Learning 🚗

## 📌 Project Overview

This project is part of the **OASIS Infobyte Data Science Internship – Task 3**.

The objective of this project is to build a **machine learning regression model** that predicts the selling price of a used car based on features such as brand, age, mileage, fuel type, and transmission.

The project involves data cleaning, exploratory data analysis, preprocessing, model training, and evaluation.

---

## 🎯 Objective

To build a machine learning model that predicts the selling price of used cars based on:

- Car Brand
- Car Age
- Mileage
- Fuel Type
- Transmission
- Other relevant vehicle features

The project aims to understand the factors that influence used-car prices and develop a regression model for price prediction.

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 📊 Dataset

The project uses a used-car dataset containing information about different cars and their selling prices.

### Features

| Feature | Description |
|---|---|
| Brand | Brand or manufacturer of the car |
| Age | Age of the car |
| Mileage | Distance travelled by the car |
| Fuel Type | Type of fuel used by the car |
| Transmission | Transmission type of the car |
| Selling Price | Price at which the car is sold |

> **Note:** The exact feature names may vary depending on the selected dataset.

---

## 🔍 Project Workflow

The project follows these steps:

1. Load the car price dataset.
2. Inspect the dataset structure.
3. Check the shape of the dataset.
4. Check for missing/null values.
5. Check and remove duplicate records.
6. Analyze numerical and categorical features.
7. Perform exploratory data analysis.
8. Handle categorical variables.
9. Prepare the dataset for machine learning.
10. Split the data into training and testing sets.
11. Train regression models.
12. Predict car selling prices.
13. Evaluate model performance.
14. Visualize actual and predicted prices.
15. Compare model performance.

---

## 🧹 Data Preprocessing

The dataset is cleaned and prepared before training the machine learning models.

The following preprocessing steps are performed:

- Check for missing values.
- Remove duplicate records.
- Handle missing values where required.
- Check data types.
- Identify numerical and categorical features.
- Encode categorical variables.
- Prepare features and target variable.
- Split the dataset into training and testing data.

The target variable is the **selling price of the car**.

---

## 📈 Exploratory Data Analysis

The following analyses and visualizations are performed to understand the factors affecting car prices:

### 1. Dataset Overview

The dataset is inspected using:

- `head()`
- `shape`
- `info()`
- `describe()`

This provides an overview of the dataset and its features.

---

### 2. Car Price Distribution

The distribution of selling prices is visualized using a histogram.

This helps understand the range and distribution of car prices in the dataset.

---

### 3. Car Price vs Age

The relationship between car age and selling price is analyzed using a visualization.

This helps understand how the age of a vehicle is associated with its selling price.

---

### 4. Car Price vs Mileage

Mileage is analyzed against selling price to understand the relationship between distance travelled and car value.

---

### 5. Fuel Type and Selling Price

The selling prices of cars with different fuel types are compared.

This helps identify differences in price distributions among fuel categories.

---

### 6. Transmission and Selling Price

Cars are grouped based on transmission type and their selling prices are compared using visualizations.

---

### 7. Correlation Analysis

A correlation heatmap is created for the numerical features.

The heatmap helps identify relationships between variables that may influence car prices.

---

## 🤖 Machine Learning Models

Regression algorithms are used to predict the selling price of cars.

The project can include models such as:

- **Linear Regression**
- **Decision Tree Regression**
- **Random Forest Regression**

The models are trained using the training dataset and evaluated using the testing dataset.

---

## 📏 Model Evaluation

The regression models are evaluated using:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

These metrics help measure how accurately the models predict the selling prices of used cars.

---

## 📊 Results

The trained regression models are used to predict car selling prices.

The project compares the performance of the trained models using different evaluation metrics.

An **Actual vs Predicted Price** visualization is also created to compare the actual selling prices with the prices predicted by the machine learning model.

The complete model results and evaluation metrics are available in the Jupyter Notebook.

---

## 📊 Visualizations

The project includes the following visualizations:

- Dataset overview
- Selling price distribution
- Car age vs selling price
- Mileage vs selling price
- Fuel type vs selling price
- Transmission vs selling price
- Correlation heatmap
- Actual vs predicted prices
- Model performance comparison

---

## 📁 Project Structure

```text
DataScience-Level3-CarPricePrediction/
│
├── Car_Price_Prediction.ipynb
├── README.md
├── dataset.csv
│
└── screenshots/
    ├── dataset_preview.png
    ├── dataset_info.png
    ├── price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── model_comparison.png
▶️ How to Run
1. Clone the repository
git clone <your-github-repository-url>

2. Open the project folder
cd OIBSIP/DataScience-Level3-CarPricePrediction

3. Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

4. Start Jupyter Notebook
jupyter notebook

5. Open
Car_Price_Prediction.ipynb

Run the cells sequentially to reproduce the analysis and results.
💡 Key Learning Outcomes
Through this project, I learned:
- Loading and inspecting real-world datasets using Pandas.
- Cleaning and preprocessing datasets.
- Handling missing values and duplicate records.
- Working with numerical and categorical data.
- Performing Exploratory Data Analysis.
- Creating data visualizations using Matplotlib and Seaborn.
- Encoding categorical variables.
- Preparing data for machine learning.
- Building regression models using Scikit-learn.
- Evaluating regression models using MAE, MSE, RMSE, and R².
- Comparing machine learning model performance.
- Understanding factors that influence used-car prices.
