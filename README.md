# MSCS 634 - Lab 4: Regression Analysis with Regularization Techniques

## Student Information

- **Student Name:** Gowtam Vidiyala
- **Course:** MSCS 634 – Machine Learning
- **Lab:** Lab 4 – Regression Analysis with Regularization Techniques


---

# Overview

This lab focuses on implementing and evaluating different regression techniques using the Diabetes dataset provided by the Scikit-learn library. The primary objective is to understand how different regression models perform on the same dataset and how regularization techniques help improve model generalization by reducing overfitting.

The regression models implemented in this lab include:

- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression

Each model was evaluated using standard regression performance metrics and visualized to better understand its predictive capability.

---

# Objectives

The objectives of this lab are:

- Load and prepare the Diabetes dataset for regression analysis.
- Perform exploratory data analysis.
- Implement Simple Linear Regression using one independent feature.
- Implement Multiple Linear Regression using all available features.
- Build a Polynomial Regression model to capture nonlinear relationships.
- Apply Ridge Regression and Lasso Regression to understand the effect of regularization.
- Evaluate each model using regression performance metrics.
- Compare the strengths and weaknesses of different regression techniques.

---

# Dataset

The Diabetes dataset is obtained from the **sklearn.datasets** module.

It contains measurements collected from diabetes patients, including variables such as:

- Age
- Sex
- Body Mass Index (BMI)
- Blood Pressure
- Cholesterol Measurements
- Additional Health Indicators

The target variable represents the quantitative measure of disease progression one year after baseline.

---

# Regression Models Implemented

## 1. Simple Linear Regression

A Simple Linear Regression model was created using BMI as the independent variable to predict disease progression.

---

## 2. Multiple Linear Regression

A Multiple Linear Regression model was developed using all available features in the dataset.

---

## 3. Polynomial Regression

Polynomial Regression was implemented by extending the linear model using polynomial features to capture nonlinear relationships between BMI and the target variable.

---

## 4. Ridge Regression

Ridge Regression was implemented using L2 regularization to reduce overfitting by shrinking coefficient values.

---

## 5. Lasso Regression

Lasso Regression was implemented using L1 regularization, allowing less significant coefficients to shrink toward zero and perform feature selection.

---

# Evaluation Metrics

Each regression model was evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

These metrics were used to compare the prediction accuracy and overall performance of each regression model.

---

# Key Insights

Several important observations were made during this lab:

- Multiple Linear Regression performed better than Simple Linear Regression because it utilized all available input features.
- Polynomial Regression successfully captured nonlinear relationships but may become more susceptible to overfitting as the polynomial degree increases.
- Ridge Regression improved model stability by reducing the magnitude of regression coefficients through L2 regularization.
- Lasso Regression reduced less important feature coefficients toward zero, effectively performing feature selection.
- Comparing RMSE and R² values made it easier to determine which model produced the best predictions.
- Feature engineering and regularization significantly influence regression model performance.

---

# Challenges Faced

During this lab, several challenges were encountered:

- Understanding the differences between Simple, Multiple, and Polynomial Regression.
- Selecting an appropriate polynomial degree to balance underfitting and overfitting.
- Understanding how Ridge and Lasso regularization affect regression coefficients.
- Comparing multiple evaluation metrics to identify the best-performing model.
- Interpreting regression coefficients and model predictions accurately.

---

# Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# Conclusion

This lab provided practical experience in implementing several regression algorithms and comparing their performance on the Diabetes dataset.

Simple Linear Regression established a baseline model, while Multiple Linear Regression improved prediction accuracy by incorporating all available features. Polynomial Regression demonstrated the ability to model nonlinear relationships, whereas Ridge and Lasso Regression illustrated how regularization techniques improve model generalization and reduce overfitting.

Overall, the lab emphasized the importance of selecting an appropriate regression technique based on the characteristics of the dataset and evaluating models using multiple performance metrics.

---

# Repository Contents

```
MSCS_634_Lab_4/
│
├── Lab4.ipynb
├── README.md
└── Lab4.docs
```

---

# References

1. Scikit-learn Documentation: https://scikit-learn.org/stable/
2. Diabetes Dataset Documentation: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html
3. Géron, A. *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*. O'Reilly Media.
4. Hastie, T., Tibshirani, R., & Friedman, J. *The Elements of Statistical Learning*.
