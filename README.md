# 🏡 Predicting Housing Market Trends with AI
Machine Learning & AI Models Using the Kaggle Advanced House Price Dataset
## 📌 Project Overview

This project aims to accurately predict housing prices using the Kaggle Advanced House Price Prediction dataset.
The dataset contains 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa.
The goal of this project is to:

- Build a full end-to-end ML workflow

- Compare classical ML, tree-based models, and neural networks

- Implement feature engineering and hyperparameter tuning

- Evaluate model performance

- Provide insights and actionable recommendations

This project demonstrates strong knowledge of data preprocessing, modeling, optimization, and ML evaluation—essential skills for data science and machine learning roles.

## 🧩 Business Problem

Accurately pricing houses is a critical challenge for:

- Real-estate agencies

- Property investors

- Mortgage lenders

- Housing market analysts

- Government planning departments

Inaccurate pricing leads to:

- Lost revenue

- Inefficient inventory movement

- Poor investment decisions

- Market imbalance

This project solves the problem by building AI-powered predictive models that capture nonlinear patterns, housing quality, renovation impact, and neighborhood characteristics.

## 🎯 Business Value / Impact

- Enables data-driven pricing decisions

- Reduces financial risk for lenders and investors

- Helps agencies optimize listing prices

- Improves market trend forecasting

- Enhances transparency in the housing market

- AI-driven price predictions can improve pricing accuracy by 15–30%, increasing competitiveness and market confidence.

## 📂 Dataset

- Source: Kaggle — House Prices: Advanced Regression Techniques
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

- Key characteristics:

      - 79 features (numerical + categorical)

      - Information on structure, quality, materials, condition, neighborhood

- Target: SalePrice

## ⚙️ Workflow Summary

- Exploratory Data Analysis (EDA)

- Data Cleaning & Missing Value Handling

- Label Encoding & Feature Scaling

- Advanced Feature Engineering:

      - House age

      - Total bathrooms

      - Total porch area

      - Quality index

      - Interaction terms

      - Log transform of skewed features

- Model Training

- Hyperparameter Tuning

- Evaluation using RMSE, MAE, R²

- Insights & Recommendations

## 🤖 Models Used

- Linear Regression

- Random Forest Regressor

- XGBoost Regressor

- Neural Network (MLP)

## 📊 Model Performance

| Model               | RMSE       | MAE        | R²         |
| ------------------- | ---------- | ---------- | ---------- |
| Linear Regression   | 0.1734     | 0.0960     | 0.8389     |
| Random Forest       | 0.1478     | 0.0972     | 0.8830     |
| Neural Network      | 0.1555     | 0.1043     | 0.8704     |
| **XGBoost (Tuned)** | **0.1243** | **0.0858** | **0.9073** |


## 🔍 Insights
 ✔ XGBoost is the best-performing model
- It captures complex nonlinear relationships and interactions far better than linear or tree-averaged models.

 ✔ Neural Networks do not outperform boosting models
- This dataset is tabular and structured, where neural networks usually struggle without massive data or embeddings.

 ✔ Feature engineering significantly improved performance
- Interactions between quality, size, and age provided major predictive gains.

✔ Linear Regression underfits the problem
- Housing prices contain nonlinear patterns that simple models cannot capture.

✔ Hyperparameter tuning significantly improved the model’s generalization ability.
- The tuned XGBoost model is recommended as the primary candidate for deployment, or as the meta-learner in a stacking ensemble.

## 🛠 How to Run the Project

- Download
- Open on goggle colab or Jupytier Notebook
- Run all

 ## 👤 Author

- Faheemunnisa Syeda
- Machine Learning & Applied Math Specialist
- 📧 syedafaheem7@gmail.com
- 🔗 GitHub: [https://github.com/syedafaheem7/]
- 🔗 linkedln: [https://www.linkedin.com/in/faheem-unnisa-s-6270888b/]
