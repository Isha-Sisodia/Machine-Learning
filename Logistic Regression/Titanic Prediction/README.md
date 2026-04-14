# 🚢 Titanic Survival Prediction using Logistic Regression

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using a Logistic Regression model. It is a classic binary classification problem in machine learning.

---

## Objective

To build a predictive model that classifies passengers as:

* **0 → Did Not Survive**
* **1 → Survived**

---

## Dataset

Dataset Link - https://www.kaggle.com/competitions/titanic

The dataset consists of three files:

* `train.csv` → Used for training the model
* `test.csv` → Used for making predictions
* `gender_submission.csv` → Sample submission format

---

## Technologies Used

* Python
* Pandas
* Scikit-learn

---
## Workflow

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Feature selection
4. Model training
5. Prediction on test data
6. Submission file generation

---
## Data Preprocessing

* Handled missing values:

  * `Age` → filled using median
  * `Embarked` → filled using mode
  * `Fare` → filled using median
* Dropped `Cabin` column due to excessive missing values
* Converted categorical data into numerical format:

  * `Sex` → male: 0, female: 1
  * `Embarked` → S: 0, C: 1, Q: 2

---
## Model Used

* Logistic Regression

---

## Key Learnings

* Handling missing data
* Encoding categorical variables
* Building a classification model
* Importance of data preprocessing
* Understanding model evaluation using Kaggle leaderboard

---

## 📁 Output

* `submission.csv` → Final predictions ready for Kaggle submission

## 📊 Result

* Achieved a **Kaggle Public Score of 0.76315 (~76% accuracy)**
* The model successfully predicts survival outcomes for unseen data

---

## 🏆 Achievements

- Earned **"Getting Started Competitor" Badge** on Kaggle  
- Successfully submitted a machine learning model in a real-world competition  
- Gained hands-on experience in end-to-end ML workflow  


---
