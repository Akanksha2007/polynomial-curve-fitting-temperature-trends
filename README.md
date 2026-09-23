# Polynomial Curve Fitting for Temperature Trends

## 📌 Project Overview

This project explores **Polynomial Regression** for analyzing and predicting temperature trends using historical climate data.

The main objective is to understand how model complexity affects prediction performance and to demonstrate important machine learning concepts such as **underfitting, overfitting, and the bias-variance trade-off**.

---

## 🎯 Objectives

- Analyze historical temperature data
- Visualize temperature trends
- Apply Polynomial Regression
- Compare models with different polynomial degrees
- Understand underfitting and overfitting
- Study the bias-variance trade-off
- Perform chronological train-test validation
- Evaluate model performance using different metrics
- Select an appropriate model based on validation performance

---

## 📊 Dataset

The project uses historical climate/temperature data for Delhi.

Time-related features such as **day of the year** are used to capture seasonal temperature patterns.

---

## 🧠 Machine Learning Approach

Polynomial Regression models with different degrees were compared:

| Polynomial Degree | Purpose |
|---|---|
| Degree 1 | Demonstrates underfitting |
| Degree 3 | Captures a simple nonlinear trend |
| Degree 9 | Captures more complex patterns |
| Degree 20 | Demonstrates overfitting |

The experiments show that increasing model complexity does not always improve performance on unseen data.

---

## 🔬 Project Workflow

1. Import and inspect the dataset
2. Perform Exploratory Data Analysis
3. Visualize temperature patterns
4. Prepare features and target variables
5. Split the data chronologically
6. Apply Polynomial Regression
7. Compare different polynomial degrees
8. Analyze underfitting and overfitting
9. Perform feature engineering using seasonal information
10. Evaluate models using RMSE, MAE, and R²
11. Select the final model based on validation performance
12. Evaluate the final model on held-out data

---

## 📈 Evaluation Metrics

The models are evaluated using:

### RMSE
Root Mean Squared Error measures the average prediction error while giving more weight to larger errors.

### MAE
Mean Absolute Error measures the average absolute difference between predicted and actual temperature.

### R² Score
R² measures how well the model explains the variation in the target variable.

---

## 📌 Final Model Performance

The final held-out evaluation achieved approximately:

| Metric | Score |
|---|---:|
| RMSE | 2.87°C |
| MAE | 2.26°C |
| R² Score | 0.79 |

---

## 💡 Key Learning

A major observation from this project is that **higher polynomial degree does not automatically mean better performance**.

A very high-degree polynomial can fit the training data extremely closely but may perform poorly on unseen data. This is an example of **overfitting**.

The project demonstrates why selecting an appropriate model complexity and using validation data are important for building models that generalize well.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Google Colab

---

## 📂 Repository Structure

```text
polynomial-curve-fitting-temperature-trends/
│
├── Polynomial_Curve_Fitting_Temperature_Trend.ipynb
└── README.md
