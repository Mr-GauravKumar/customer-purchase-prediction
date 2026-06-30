# Customer Purchase Prediction

Customer Purchase Value Prediction Project with Multi-Session Digital Behavior Data. Data preprocessing, missing value analysis, exploratory data analysis (EDA), feature-target relationship analysis, log transformation, and XGBoost regression modeling to predict customer purchase potential based on their behavioral data and traffic sources.

---------------------------------------------------------------------------------------------------------------------------

# Customer Purchase Prediction

Predicting customer purchase value using multi-session behavioral and digital interaction data with Machine Learning.

---

# Project Overview

This project focuses on analyzing customer behavior data and predicting purchase value based on:
- Browser usage
- Traffic source
- Device type
- Geographic information
- User interaction patterns

The objective is to estimate customer purchase potential using regression-based machine learning models.

---

# Workflow


Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Model Training (XGBoost)
        ↓
Model Evaluation
        ↓
Prediction & Submission



---

# Dataset Features

## Categorical Features
- browser
- deviceType
- trafficSource.medium
- trafficSource.campaign
- locationCountry
- geoNetwork.city
- geoNetwork.region
- geoNetwork.continent
- userChannel

## Numerical Features
- geoCluster

---

# Exploratory Data Analysis (EDA)

## Missing Value Analysis



Performed missing value analysis to identify incomplete columns and understand dataset quality.

---

## Target Distribution Analysis


Analyzed the distribution of purchase values to detect skewness and outliers.

---

## Log Transformation



Applied log transformation to reduce skewness and stabilize the target distribution.

---

## Browser Distribution



Analyzed the most commonly used browsers across customer sessions.

---

## Device Type Analysis

Studied customer device usage patterns.

---

## Traffic Source Analysis



Explored customer acquisition channels and traffic behavior.

---

## Feature vs Target Relationship
<img width="568" height="363" alt="image" src="https://github.com/user-attachments/assets/b7104403-9a3b-427c-90c8-27696ca0c099" />
Boxplot



<img width="549" height="364" alt="image" src="https://github.com/user-attachments/assets/5e847381-1416-493e-a0e9-b495c4bd9c02" />
ViolinPlot

Compared purchase value distribution across device categories.

---

## Correlation Heatmap

<img width="730" height="686" alt="image" src="https://github.com/user-attachments/assets/de67b461-eec7-45db-a31a-194fb5795614" />



Analyzed relationships between numerical features.

---

# Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Duplicate removal
- Feature selection
- Encoding categorical features
- Log transformation of target variable

---

# Machine Learning Model
<img width="572" height="370" alt="image" src="https://github.com/user-attachments/assets/742cf667-dd9d-42b1-b98e-88c697502ee5" />

## Model Used
- XGBoost Regressor

## Why XGBoost?
- Strong performance on tabular data
- Handles complex feature interactions
- Effective for regression problems

---

# Model Evaluation

## Evaluation Metrics
- R² Score
- RMSE
- MAE



---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

# Project Structure

```bash
Customer-Purchase-Prediction/
│
├── notebook/
├── images/
├── submission/
├── README.md
```

---

# Future Improvements

- Advanced feature engineering
- Hyperparameter tuning
- Ensemble learning
- Better handling of high-cardinality features

---

# Kaggle Competition
MLP Project

---

# Author
Gaurav Kumar | IIT Madras
