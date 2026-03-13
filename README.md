# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project builds a machine learning model to detect fraudulent credit card transactions. 
Credit card fraud detection is an important problem in the financial sector because fraudulent transactions can lead to significant financial losses.

The dataset used in this project is highly imbalanced, with fraudulent transactions representing a very small percentage of the total transactions.

## Objectives

- Understand and explore the transaction dataset
- Perform data preprocessing and feature scaling
- Conduct exploratory data analysis (EDA)
- Train machine learning models to detect fraud
- Evaluate models using appropriate metrics such as Precision, Recall, and F1-score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data Understanding
   - Checked dataset structure
   - Verified missing values
   - Identified class imbalance

2. Data Preprocessing
   - Removed duplicate records
   - Scaled the transaction amount feature
   - Dropped unnecessary columns
   - Performed train-test split

3. Exploratory Data Analysis
   - Fraud vs normal transaction distribution
   - Transaction amount analysis
   - Correlation analysis between features

4. Model Training
   - Logistic Regression
   - Decision Tree Classifier

5. Model Evaluation
   - Confusion Matrix
   - Precision
   - Recall
   - F1 Score
   - ROC Curve

## Dataset

The dataset used in this project can be downloaded from:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Key Insights

- Fraud transactions account for only about **0.17%** of the dataset.
- The dataset is highly imbalanced.
- Accuracy alone is not a reliable metric for fraud detection.
- Precision and Recall are more important for evaluating the model.

## Future Improvements

- Handle class imbalance using SMOTE
- Try advanced models such as Random Forest or XGBoost
- Deploy the model using Streamlit or Flask

## Author
Sangram Choudhury

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Project Structure
