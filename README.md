# Anxiety Prediction Using Machine Learning

## Overview

This project develops machine learning models to predict anxiety using a structured dataset. The project explores both regression and classification approaches. Initially, regression models were trained to predict the numerical anxiety score. The numerical scores were then categorized into three classes (Low, Medium, and High) to build classification models for anxiety level prediction.

The project follows a complete machine learning pipeline, including data preprocessing, feature engineering, model training, hyperparameter tuning, performance evaluation, and comparison of multiple algorithms.

---

## Objectives

- Predict anxiety using machine learning techniques.
- Compare the performance of multiple regression models.
- Convert numerical anxiety scores into Low, Medium, and High categories.
- Build and evaluate classification models.
- Identify the best-performing model through systematic evaluation.

---

## Dataset

The dataset contains demographic, lifestyle, and health-related features associated with anxiety.

**Target Variables**
- Regression: Numerical Anxiety Score
- Classification: Anxiety Level (Low, Medium, High)

---

## Project Workflow

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding and Scaling
- Correlation Analysis
- Removal of Highly Correlated Features
- Data Leakage Validation using Label Shuffling
- Train-Test Split
- SMOTE for Class Imbalance (Classification Only)
- Model Training
- Hyperparameter Tuning using GridSearchCV
- Cross-Validation
- Model Evaluation and Comparison

---

## Regression Models

- Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Classification Models

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree Classifier
- Random Forest Classifier

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Model Optimization

The project improves model performance using:

- SMOTE to handle class imbalance
- GridSearchCV for hyperparameter tuning
- Cross-validation for robust model evaluation

---

## Results

The performance of both regression and classification models was compared using appropriate evaluation metrics.

Among the regression algorithms, Random Forest Regressor achieved the strongest predictive performance.

For the classification task, Random Forest Classifier delivered the highest accuracy after applying SMOTE and hyperparameter tuning, outperforming the other classification models.

---
## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)

---
## Future Improvements

- Test additional ensemble learning techniques.
- Explore XGBoost and LightGBM models.
- Deploy the best-performing model as a web application.
- Perform feature selection using advanced techniques.
---

## Author

**Javeria Salman**

Machine Learning | Data Science | Software Engineering Student
