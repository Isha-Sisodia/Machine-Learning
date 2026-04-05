# Salary Prediction using Machine Learning

## Project Overview

This project predicts a person's **salary based on years of experience** using a simple Machine Learning model called **Linear Regression**.

It is one of the most fundamental ML projects and helps understand how models learn relationships between variables.

---

## Objective

To build a model that can:

* Take **Years of Experience** as input
* Predict **Salary** as output

---

## Concept Used

* Linear Regression
* Train-Test Split
* Model Evaluation (R² Score)

---

## Dataset

The dataset contains two columns:

| Feature         | Description                        |
| --------------- | ---------------------------------- |
| YearsExperience | Number of years of experience      |
| Salary          | Salary corresponding to experience |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Steps Performed

### 1. Import Libraries

* Loaded required Python libraries

### 2. Load Dataset

* Read CSV file using Pandas

### 3. Data Preprocessing

* Defined input (X) and output (y)

### 4. Train-Test Split

* Split data into:

  * 80% Training Data
  * 20% Testing Data

### 5. Train Model

* Used Linear Regression to train model

### 6. Make Predictions

* Predicted salary using test data

### 7. Visualization

* Plotted:

  * Actual data points
  * Regression line

### 8. Model Evaluation

* Used R² Score to measure accuracy

### 9. Predict Custom Input

* Example: Predict salary for 5 years experience

---

## Model Equation

The model follows:

Salary = m × Experience + b

Where:

* m = slope (salary increase per year)
* b = intercept (base salary)

---

## Results

* Model successfully predicts salary based on experience
* Predictions are close to actual values
* High R² score indicates good performance

---

## Sample Prediction

Input:
5 years experience

Output:
Predicted Salary ≈ ₹72,000 (may vary depending on dataset)

---

## Actual vs Predicted

The comparison between actual and predicted values shows that:

* The model performs well
* Error is minimal
* Points lie close to ideal line (y = x)

---

## Important Learnings

* Always split data into training and testing
* Never train on full dataset
* Use consistent feature names during prediction
* Visualization helps understand model performance

---

## Project Structure

```
Salary-Prediction/
│── Salary_Data.csv
│── ML_model.ipynb
│── README.md
```

---

## Conclusion

This project demonstrates how Machine Learning can be used to:

* Identify patterns in data
* Make predictions
* Solve real-world problems

