# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project presents an end-to-end Machine Learning solution for predicting residential property prices using the Ames Housing Dataset. The objective is to estimate house prices based on key structural and quality-related attributes through data analysis, feature engineering, and Linear Regression modeling.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature selection, model training, evaluation, and prediction.

---

## 🎯 Problem Statement

Accurately estimating property values is a critical task in the real estate industry. The goal of this project is to develop a predictive model capable of estimating house prices using important housing characteristics such as living area, overall quality, garage specifications, basement area, bathrooms, and construction year.

---

## 📊 Dataset Information

**Dataset:** Ames Housing Dataset

* Total Records: 1,460
* Total Features: 81
* Target Variable: `SalePrice`

The dataset contains detailed information about residential properties, including physical attributes, construction quality, location characteristics, and sale information.

---

## 🔍 Exploratory Data Analysis

The dataset was analyzed to understand:

* Data structure and feature types
* Missing value patterns
* Distribution of house prices
* Feature correlations
* Important predictors of property value

### Key Observations

* House prices exhibit a positively skewed distribution.
* Overall quality is the strongest predictor of house prices.
* Living area, garage capacity, basement area, and year built significantly influence property value.
* Several features contain missing values representing the absence of specific facilities (e.g., pool, fence, alley access).

---

## ⚙️ Feature Selection

The following features were selected based on correlation analysis and domain relevance:

| Feature     | Description                         |
| ----------- | ----------------------------------- |
| OverallQual | Overall material and finish quality |
| GrLivArea   | Above-ground living area (sq ft)    |
| GarageCars  | Garage capacity in number of cars   |
| GarageArea  | Garage area (sq ft)                 |
| TotalBsmtSF | Total basement area (sq ft)         |
| FullBath    | Number of full bathrooms            |
| YearBuilt   | Year the house was built            |

### Target Variable

* SalePrice

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab
* GitHub

---

## 🤖 Machine Learning Model

### Algorithm Used

**Linear Regression**

Linear Regression was selected to model the relationship between housing attributes and property prices, providing an interpretable baseline model for house price prediction.

---

## 📈 Model Performance

| Metric                         | Value  |
| ------------------------------ | ------ |
| Mean Absolute Error (MAE)      | 25,121 |
| Root Mean Squared Error (RMSE) | 39,652 |
| R² Score                       | 0.795  |

### Interpretation

The model achieved an **R² Score of 0.795**, indicating that approximately **79.5% of the variance in house prices** can be explained by the selected features.

---

## 🔮 Sample Prediction

### Input

* Overall Quality: 5
* Living Area: 1500 sq ft
* Garage Capacity: 2 Cars
* Garage Area: 300 sq ft
* Basement Area: 500 sq ft
* Bathrooms: 2
* Year Built: 2006

### Predicted Output

**Predicted House Price: $153,781.09**

---

## 📂 Project Workflow

1. Data Collection and Loading
2. Data Understanding
3. Missing Value Analysis
4. Exploratory Data Analysis (EDA)
5. Correlation Analysis
6. Feature Selection
7. Data Validation
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. House Price Prediction

---

## 🚀 Future Enhancements

* Streamlit Web Application
* Advanced Regression Algorithms
* Hyperparameter Optimization
* Model Serialization and Deployment
* Interactive User Interface
* Cloud Deployment

---

## 📚 Skills Demonstrated

* Data Analysis
* Data Visualization
* Feature Engineering
* Machine Learning
* Regression Modeling
* Model Evaluation
* Python Programming
* GitHub Project Management

---

## 👨‍💻 Author

**NALANAGULA DEEPANJAN**

Machine Learning Enthusiast | AI & Data Science Learner
