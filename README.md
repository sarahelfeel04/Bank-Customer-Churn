# Bank Customer Churn Classification

## Overview
This project aims to predict bank customer churn using a dataset containing customer demographics, credit scores, and balance. The project involves data exploration, preprocessing, model training, and evaluation. Various machine learning algorithms were implemented and optimized to achieve the best performance.

---

## Dataset
The dataset used in this project contains features about customers at the bank. To download and view the dataset, click [here](https://drive.google.com/file/d/15GaO6TpEP441FjMS-IhgBFCOhxkkTHuL/view?usp=sharing).

---

## Project Steps
1. **Data Exploration**: Initial exploration of the dataset to understand the distribution of features and identify missing values.
2. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
3. **Data Visualization**: Visualizing data to uncover insights about customer behavior
4. **Model Training**: Training various machine learning models including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, HistGradientBoosting.
5. **Model Evaluation**: Evaluating model performance using F1 score and ROC AUC.
6. **Hyperparameter Optimization**: Using GridSearchCV and RandomizedSearchCV to optimize model hyperparameters.
7. **Final Model Selection**: Selecting the best-performing model based on evaluation metrics. 
   
---

## Results
The best-performing model achieved an ROC AUC of 93.1% on the test and train dataset was Gradient Boosting with hyperparameter tuning and feature selector.

---

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   ```
2. Run the Jupyter notebook and change dataset path


