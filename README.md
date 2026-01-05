# AI_Customer_Churn_Project
End-to-end Customer Churn Analysis and ML project with Business Insights
# Customer Churn Prediction – End-to-End Machine Learning Project

## Overview
This project builds an end-to-end machine learning solution to predict customer churn in a telecom business. The goal is to identify customers at risk of churning and provide actionable insights to improve retention strategies.

## Business Problem
Customer churn leads to direct revenue loss and increased acquisition costs. Early identification of high-risk customers enables proactive retention efforts and better resource allocation.

## Project Workflow
1. Business Understanding
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Building & Evaluation
6. Model Selection

## Key Insights from EDA
- Overall churn rate is ~26.5%
- Month-to-month contracts show significantly higher churn
- Early-tenure customers are more likely to churn
- Higher monthly charges increase churn risk
- Higher service engagement reduces churn probability

## Feature Engineering Highlights
- New customer flag based on tenure
- Pricing sensitivity indicator
- Customer engagement score based on services used
- Charges-per-tenure feature to capture lifecycle value
- Payment risk indicator

## Models Evaluated
- Logistic Regression (baseline, interpretable)
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost

## Final Model
**XGBoost** was selected as the final model based on:
- Highest test accuracy
- Strong churn recall
- Good generalization
- Ability to model non-linear patterns

Classification threshold tuning was applied to improve recall for churners, aligning predictions with business retention priorities.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## Outcome
The final model provides a robust and business-aligned solution for churn prediction, enabling targeted retention strategies and data-driven decision-making.
