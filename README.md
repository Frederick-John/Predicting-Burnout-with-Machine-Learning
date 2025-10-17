🔥 Predicting Burnout with Machine Learning

📘 Overview

This is a Python development project created for the PLP Academy. It focuses on predicting employee burnout using machine learning techniques. The project demonstrates practical skills in Python programming, data preprocessing, exploratory data analysis (EDA), feature engineering, and regression model development.

🎯 Objectives
Analyze employee-level data to understand burnout patterns

Clean and preprocess raw data for modeling

Engineer meaningful features to improve prediction accuracy

Train and evaluate regression models

Generate insights to support workplace well-being strategies

📂 Dataset

The project uses two CSV files:

train.csv: labeled data for training and analysis

test.csv: unlabeled data for prediction

Key features include:

Gender, Company Type, WFH Setup

Designation, Resource Allocation

Mental Fatigue Score, Date of Joining

Burn Rate (target variable)

🔍 Exploratory Data Analysis (EDA)
Summary statistics and data types

Missing value handling

Distribution plots and boxplots

Correlation heatmap and pairplots

⚙️ Data Preprocessing
Label encoding for categorical variables

Median imputation for missing values

Min-Max normalization for selected features

Feature engineering: Tenure (Years) from Date of Joining

🤖 Model Development
Regression models trained:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Evaluation Metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Best-performing model: Gradient Boosting Regressor

R²: 0.8599

MAE: 0.0522

MSE: 0.005

📈 Feature Importance
Top predictors of burnout:

Mental Fatigue Score

Tenure (Years)

Resource Allocation

Designation

Company Type

💡 Insights
Employees with high mental fatigue and long tenure are more prone to burnout

Resource allocation and designation levels significantly influence burnout risk

Organizational type and WFH setup also play a role

🧠 Author
Frederick Kelvin Ohwoavworiete Python Developer | PLP Academy Trainee
