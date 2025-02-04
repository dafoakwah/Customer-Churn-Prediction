# Customer Churn Prediction

## Overview

This project aims to predict customer churn in a banking institution using machine learning. By analyzing customer data, we identify key factors that influence churn and build predictive models to classify customers as likely to stay or leave.

## Dataset

The dataset contains information about **10,000 customers**, including features such as:

- **Credit Score**
- **Geography**
- **Gender**
- **Age**
- **Tenure** (Years with the bank)
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited** (Target variable: 1 = Churned, 0 = Stayed)

## Steps Taken

### 1. Exploratory Data Analysis (EDA)

- Checked missing values and data distribution
- Visualized features using **histograms, box plots, heatmaps, and pie charts**
- Analyzed feature importance and correlation with churn

### 2. Data Preprocessing

- **Encoded categorical variables** (`Geography`, `Gender`)
- **Scaled numerical features** using `StandardScaler`
- **Split data** into **80% training and 20% testing**

### 3. Model Training & Evaluation

Trained multiple classification models:

- **Logistic Regression**
- **Decision Tree**
- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Gradient Boosting Classifier**

Evaluated models using:

- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)
- **Confusion Matrix**
- **ROC AUC Score**

### 4. Results

- The best-performing model achieved **87% accuracy**
- Key predictors of churn include **Age, Balance, and Number of Products**

## Future Improvements

- **Hyperparameter tuning** for better accuracy
- Implement **Random Forest, XGBoost, or Neural Networks**
- Feature engineering for deeper insights
- Deploy model as a **web application or API**

## Technologies Used

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Machine Learning Models** (Logistic Regression, Decision Tree, SVC, KNN, Gradient Boosting)
- **Jupyter Notebook** for development
