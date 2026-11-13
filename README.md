# Task 35 — Regression Model Evaluation Using Python

## Project Overview

This project demonstrates how to evaluate a Linear Regression model using Mean Absolute Error (MAE) and Mean Squared Error (MSE).

A Salary vs Experience Dataset is used to predict annual salary based on years of work experience.

The project compares actual and predicted salary values and calculates regression evaluation metrics using Scikit-learn.

## Objectives

- Understand regression model evaluation.
- Prepare a salary and experience dataset.
- Train a Linear Regression model.
- Generate predictions on test data.
- Calculate Mean Absolute Error.
- Calculate Mean Squared Error.
- Compare actual and predicted values.
- Interpret the evaluation results.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Dataset Description

The project uses a manually created dataset containing 20 fictional employee records.

| Column | Description |
|---|---|
| years_experience | Total years of work experience |
| annual_salary_inr | Annual salary in Indian Rupees |

## Model Used

**Algorithm:** Simple Linear Regression

**Input Feature:** `years_experience`

**Target Variable:** `annual_salary_inr`

The dataset is divided into:

- 80% training data — 16 records.
- 20% testing data — 4 records.

The model is trained using `LinearRegression()` from Scikit-learn.

## Evaluation Metrics

### Mean Absolute Error (MAE)

MAE measures the average absolute difference between actual and predicted values.

**Result: ₹5,561.38**

### Mean Squared Error (MSE)

MSE measures the average squared difference between actual and predicted values.

**Result: 31,029,545.81 squared rupees.**

## Results Interpretation

The model produces predictions that are relatively close to the actual salaries in the testing dataset.

The MAE indicates an average absolute prediction error of approximately ₹5,561.38.

MSE gives larger prediction errors greater weight because it squares the differences.

Both metrics help assess the performance of a regression model.

## Project Files

- `Task_35_Regression_Model_Evaluation.ipynb` — Complete Colab notebook.
- `salary_experience_dataset.csv` — Original salary dataset.
- `regression_predictions.csv` — Actual and predicted salary values.
- `evaluation_summary.csv` — Evaluation metrics and project summary.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `charts/actual_vs_predicted.png` — Actual versus predicted salary chart.
- `screenshots/` — Actual execution evidence.

## Conclusion

This project demonstrates how to evaluate a Linear Regression model using MAE and MSE.

The actual and predicted salary values are compared, and both metrics are calculated using the testing dataset.

The project provides practical experience in model evaluation, prediction error analysis, and interpreting regression results.

**Note:** The dataset contains fictional salary values designed to follow an approximately linear relationship. Evaluation performance on real-world data may differ.
