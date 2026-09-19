# Student Performance Prediction Using Linear Regression

## 1. Project Overview

This mini project focuses on predicting student final performance using supervised machine learning.

The project uses Python for data preprocessing, statistical analysis, exploratory data analysis (EDA), and Linear Regression.

## 2. Problem Statement

Student performance can be influenced by different academic and lifestyle-related factors. The objective of this project is to analyze these factors and predict the student's final score using Linear Regression.

## 3. Objectives

- Analyze student performance data.
- Perform data preprocessing.
- Conduct exploratory data analysis.
- Study relationships between different variables.
- Build a Linear Regression model.
- Interpret the model results.

## 4. Dataset Description

The dataset contains information about student academic and lifestyle-related factors.

### Variables

| Variable | Description |
|---|---|
| Study_Hours | Number of hours spent studying |
| Attendance | Student attendance percentage |
| Previous_Score | Previous academic score |
| Sleep_Hours | Average hours of sleep |
| Practice_Papers | Number of practice papers completed |
| Final_Score | Final score and target variable |

### Target Variable

The target variable used for prediction is `Final_Score`.

## 5. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 6. Project Methodology

The project follows these steps:

1. Data loading
2. Data preprocessing
3. Exploratory Data Analysis
4. Statistical analysis
5. Linear Regression model building
6. Model interpretation
7. Conclusion

## 7. Machine Learning Model

### Linear Regression

Linear Regression is used to predict the numerical target variable `Final_Score`.

The model uses the following input variables:

- Study_Hours
- Attendance
- Previous_Score
- Sleep_Hours
- Practice_Papers

## 8. Results

The model coefficients were analyzed to understand the relationship between the input variables and the predicted final score.

## 9. Conclusion

The project demonstrates the use of Python, statistical analysis, exploratory data analysis, and supervised machine learning to analyze and predict student performance.

## 10. Limitations

- The dataset contains a limited number of variables.
- Other factors may affect student performance.
- Model predictions may not always be accurate.
- The dataset may not represent all students or educational environments.

## 11. Project Structure

```text
Student-Performance-Prediction/
│
├── dataset/
│   └── student_performance.xlsx
│
├── notebooks/
│   └── Student_Performance_Prediction.ipynb
│
├── outputs/
│
├── README.md
│
└── requirements.txt