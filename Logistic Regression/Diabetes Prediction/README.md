# Diabetes Prediction using Logistic Regression

## Overview

This project is a **Machine Learning classification model** that predicts whether a patient has diabetes or not based on medical features. The model is built using Logistic Regression and trained on a dataset containing health-related parameters.

---

## Objective

To develop a binary classification model that can:

* Predict **0 (No Diabetes)** or **1 (Diabetes)**
* Assist in early detection using medical data

---

## Dataset Features

The dataset consists of the following attributes:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI (Body Mass Index)
* DiabetesPedigreeFunction
* Age
* Outcome (Target Variable)

Dataset link - https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## Model Used

* Logistic Regression (Binary Classification)

---

## Workflow

1. Data Loading
2. Data Preprocessing
3. Splitting Dataset (Training & Testing)
4. Model Training using Logistic Regression
5. Model Evaluation using Accuracy Score
6. Prediction on new input data

---

## Model Performance

* The model is evaluated using **accuracy score**
* Confusion matrix is used for performance visualization

---

## Challenges Faced

* Encountered **Convergence Warning** due to limited iterations
* Resolved by increasing `max_iter` value
* Warning related to feature names fixed by using proper DataFrame format

---

## Key Learnings

* Understanding of classification problems
* Importance of splitting data into training and testing sets
* Handling model warnings and improving performance
* Basics of model evaluation and prediction

---

## Future Scope

* Convert into a web application using Flask
* Add user interface for input and prediction
* Improve model accuracy using advanced algorithms

---

## Conclusion

This project demonstrates how Logistic Regression can be used effectively for solving real-world binary classification problems like diabetes prediction. It provides a strong foundation for building more advanced machine learning applications.

---
