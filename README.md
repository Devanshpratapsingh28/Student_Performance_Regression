# Student_Performance_Regression Problem

## Problem Statement :
On the basis of given dataset we need to predict students performance in high school.

## Dataset Source : https://www.kaggle.com/datasets/devansodariya/student-performance-data

### Libraries Used 
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit Learn (Sklearn)

### Observations
1. Father's and mother's education slightly affect grades of their child.
2. Grades G1,G2 and G3 are directly proportional to each other.

### Data Preprocessing Steps
1. Created seperate pipeline for numerical and categorical columns.
2. Performed a train-test split using **train_test_split** from **sklearn.model_selection**.
3. Scale the numerical inputs using **Standard Scalar** and encoded categorial inputs with **One Hot Encoding**. 

### Models Tried 
1. Logistic Regression and its varients like ridge,lasso
2. DecisionTree
3. RandomForest
4. SVM Regressor

### Accuracy Table

| Model              | MAE  | MSE   | R²   |
|--------------------|------|-------|------|
| Linear Regression  | 1.51 | 4.96  | 0.77 |
| Ridge Regression   | 1.47 | 4.79  | 0.78 |
| SVM Regressor      | 1.10 | 4.57  | 0.79 |
| Lasso Regression   | 1.25 | 4.28  | 0.81 |
| Decision Tree      | 1.13 | 4.13  | 0.81 |
| **Random Forest**  | **1.09** | **3.43**  | **0.84** |

### Best Model : Random Forest 
