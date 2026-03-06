# Student Performance Machine Learning Analysis

This project performs an end-to-end machine learning analysis on a dataset of 5,000 students to understand how lifestyle and study behaviors affect academic performance and burnout.

## Dataset

- **File:** `ultimate_student_productivity_dataset_5000.csv`
- **Records:** 5,000 student entries

## Overview

The analysis includes:

- Exploratory Data Analysis (EDA)
- Regression modeling
- Classification modeling
- Feature importance analysis
- Multi-output prediction

## Project Goals

This project answers five main questions:

- **Regression:** Predict a student's `exam_score`
- **Classification:** Identify students at risk of burnout
- **Performance Modeling:** Study relationships between focus, productivity, and exam performance
- **Feature Importance:** Determine which behaviors influence performance most
- **Multi-Output Modeling:** Predict multiple student outcomes simultaneously

### Predicted Outcomes

- `focus_index`
- `burnout_level`
- `productivity_score`
- `exam_score`

## Technologies Used

The analysis is written in **Python** using these libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### Machine Learning Models Used

- Linear Regression
- Ridge
- Lasso
- ElasticNet
- Random Forest
- Gradient Boosting
- Extra Trees
- Support Vector Machines
- K-Nearest Neighbors
- Logistic Regression
- Naive Bayes
- MultiOutputRegressor

## Project Workflow

The code performs the following steps:

### 1. Data Loading

- Loads the student dataset
- Checks the shape and preview of the data

### 2. Exploratory Data Analysis (EDA)

Uses visualizations and summary statistics to understand:

- Feature distributions
- Correlations between variables
- Relationships with exam scores
- Group differences across demographics

### 3. Data Preprocessing

Includes:

- Categorical encoding
- Feature selection
- Burnout risk label creation
- Train/test splitting
- Feature scaling

### 4. Regression Modeling

Multiple models predict `exam_score` and are compared using:

- **R²**
- **MAE**
- **RMSE**
- **Cross-validation**

### 5. Classification Modeling

Models classify students as **burnout risk** or **not at risk**.

Evaluation metrics include:

- **Accuracy**
- **F1 Score**
- **ROC-AUC**

### 6. Performance Modeling

- Studies how `focus_index` and `productivity_score` relate to `exam_score`
- Explores performance patterns through plots and correlations

### 7. Feature Importance Analysis

Important predictors are identified using:

- Random Forest importance
- Gradient Boosting importance
- Permutation importance

### 8. Multi-Output Prediction

A single model predicts multiple student outcomes at once:

- `focus_index`
- `burnout_level`
- `productivity_score`
- `exam_score`

### 9. Model Performance Summary

- Compares all models
- Visualizes final results
- Highlights the most influential features

## How to Run

1. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

2. Place the dataset file in the same folder as the script.
3. Run the Python script