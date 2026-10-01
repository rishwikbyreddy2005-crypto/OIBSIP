# Iris Flower Classification 🌸

## 📌 Project Overview

This project is part of the **OASIS Infobyte Data Science Internship – Task 1**.

The objective of this project is to build a **machine learning classification model** that identifies the species of an iris flower based on its physical measurements.

The model classifies iris flowers into three species:

- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

---

## 🎯 Objective

To train a machine learning classification model using the Iris dataset and predict the species of an iris flower based on:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

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

The Iris dataset is loaded directly using:

```python
from sklearn.datasets import load_iris
```

The dataset contains measurements of iris flowers belonging to three different species.

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |

### Target Classes

| Class | Species |
|---|---|
| 0 | Setosa |
| 1 | Versicolor |
| 2 | Virginica |

---

## 🔍 Project Workflow

The project follows these steps:

1. Load the Iris dataset.
2. Inspect the dataset structure.
3. Check for missing values.
4. Perform exploratory data analysis.
5. Visualize relationships between features.
6. Split the dataset into training and testing sets.
7. Train a classification model.
8. Make predictions on the test data.
9. Evaluate the model using classification metrics.
10. Visualize the model results.

---

## 📈 Exploratory Data Analysis

The following visualizations are performed to understand the dataset:

- Pairplot of Iris features
- Feature distribution plots
- Scatter plots
- Correlation heatmap

These visualizations help identify relationships and differences between the three iris species.

---

## 🤖 Machine Learning Model

A classification algorithm is trained using the Iris dataset.

The dataset is divided into:

- **Training data** – used to train the model
- **Testing data** – used to evaluate the model

The trained model predicts the iris species for previously unseen test samples.

---

## 📏 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

These metrics help measure how accurately the model classifies the three iris species.

---

## 📊 Results

The trained classification model successfully predicts the species of iris flowers based on their physical measurements.

The notebook contains the detailed model evaluation results, classification report, confusion matrix, and visualizations.

---

## 📁 Project Structure

```text
DataScience-Level1-IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
└── screenshots/
    ├── dataset.png
    ├── visualization.png
    └── model_results.png
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project folder

```bash
cd OIBSIP/DataScience-Level1-IrisFlowerClassification
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Iris_Flower_Classification.ipynb
```

Run the cells sequentially to reproduce the analysis and results.

---

## 💡 Key Learning Outcomes

Through this project, I learned:

- Loading datasets using Scikit-learn
- Data inspection and preprocessing
- Exploratory Data Analysis
- Data visualization using Matplotlib and Seaborn
- Splitting data into training and testing sets
- Building a classification model
- Evaluating machine learning models
- Interpreting classification metrics and confusion matrices

---

## 👨‍💻 Internship

**OASIS Infobyte – Data Science Internship**

**Task:** Task 1 – Iris Flower Classification

**Track:** Data Science

---

## 📌 Note

This project was developed as part of the **OASIS Infobyte Data Science Internship**.
