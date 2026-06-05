# Sales-Data-Analysis

## Overview

This project develops machine learning models to classify sales stages in supermarket transactions using historical sales, customer, product, and market-related information.

The study compares multiple machine learning algorithms and analyzes the factors that influence sales stage prediction.

## Objectives

* Predict sales stages from transaction and product information.
* Compare the performance of Random Forest and XGBoost models.
* Identify the most influential features affecting sales stage classification.
* Support data-driven decision making through predictive analytics.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

## Data Preparation

* Missing value analysis
* Duplicate detection
* Date feature extraction
* Label Encoding
* Data leakage prevention
* Feature scaling

## Exploratory Data Analysis (EDA)

* Numerical feature distributions
* Categorical feature analysis
* Correlation analysis
* Feature-target relationship analysis

## Models Evaluated

* Random Forest Classifier
* XGBoost Classifier

## Model Optimization

* RandomizedSearchCV
* TimeSeriesSplit Cross-Validation
* Hyperparameter Tuning

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Key Findings

* XGBoost achieved the best overall classification performance.
* Proper feature engineering and hyperparameter tuning significantly improved model accuracy.
* Product, customer, and sales-related attributes played important roles in predicting sales stages.

## Repository Structure

```text
README.md
supermarket_sales.csv

DATA MINING/
├── Biểu đồ vẽ bằng excel/
├── Kết quả dự đoán/
├── supermarket_sales(RaindomForest).ipynb
├── supermarket_sales(RandomForest).html
├── supermarket_sales(XGBoost).html
├── supermarket_sales(XGBoost).ipynb

SOURCE/

```
## Author

Le Nguyen Minh Thu
