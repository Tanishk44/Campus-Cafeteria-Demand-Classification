# 🍽️ Campus Cafeteria Demand Classification

A machine learning project that classifies cafeteria food demand into **Low, Medium, or High** based on factors such as food item, meal timing, weather, temperature, price, day of the week, exams, and holidays.

The project uses a **Random Forest Classifier** and includes an interactive prediction interface built with Python widgets.

---

## 📌 Project Overview

Managing food inventory in a campus cafeteria can be challenging because demand varies depending on different conditions.

This project uses machine learning to classify expected cafeteria demand into three categories:

- 📉 Low Demand
- 📊 Medium Demand
- 🔥 High Demand

The goal is to demonstrate how machine learning can be used to support **food planning, inventory management, and data-driven decision making**.

> **Note:** The dataset used in this project is synthetically generated for educational and demonstration purposes.

---

## 🎯 Objectives

- Analyze cafeteria food sales patterns.
- Identify factors affecting food demand.
- Perform data preprocessing and exploratory data analysis.
- Classify cafeteria demand into Low, Medium, and High categories.
- Build a machine learning classification model.
- Evaluate model performance.
- Create an interactive interface for testing new scenarios.

---

## 📊 Dataset

The dataset contains **150 records** and includes the following features:

| Feature | Description |
|---|---|
| Date | Date of the cafeteria record |
| Day | Day of the week |
| Food_Item | Name of the food item |
| Category | Food category |
| Meal_Time | Breakfast, Lunch, or Evening |
| Price | Price of the food item |
| Weather | Weather condition |
| Temperature_C | Temperature in Celsius |
| Exam_Day | Whether it is an exam day |
| Holiday | Whether it is a holiday |
| Units_Sold | Number of units sold |

### Target Variable

`Demand_Level`

The target was created from `Units_Sold`:

- **Low:** Less than 35 units
- **Medium:** 35–55 units
- **High:** More than 55 units

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab
- IPyWidgets

### Machine Learning Algorithm

**Random Forest Classifier**

The model uses:

- One-Hot Encoding for categorical features
- Numerical features such as price and temperature
- Train-test split
- Random Forest classification

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Demand Classification
   ↓
Train-Test Split
   ↓
Feature Encoding
   ↓
Random Forest Classifier
   ↓
Model Evaluation
   ↓
New Demand Prediction
   ↓
Interactive Prediction Interface
