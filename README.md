# Polynomial Curve Fitting for Temperature Trends

A machine learning project that applies **Polynomial Regression** to analyze and model historical temperature trends, with a focus on understanding **underfitting, overfitting, bias-variance trade-off, and model evaluation**.

---

## 📌 Project Overview

This project investigates how different levels of polynomial model complexity affect the ability of a regression model to learn temperature patterns and generalize to unseen data.

Polynomial Regression models with different degrees are trained and compared to demonstrate the transition from **underfitting to overfitting**.

The project also explores **seasonal feature engineering** and evaluates model performance using standard regression metrics.

---

## 🎯 Objectives

- Analyze historical temperature data using Exploratory Data Analysis (EDA)
- Visualize temperature trends and patterns
- Implement Polynomial Regression
- Compare models with different polynomial degrees
- Identify underfitting and overfitting
- Understand the bias-variance trade-off
- Use chronological train-test validation
- Apply seasonal feature engineering
- Evaluate models using RMSE, MAE, and R²
- Select an appropriate model based on validation performance

---

## 🧠 Key Machine Learning Concepts

### Polynomial Regression

Polynomial Regression extends linear regression by introducing polynomial features to model nonlinear relationships between variables.

### Underfitting

A model with insufficient complexity may fail to capture important patterns in the data.

### Overfitting

A highly complex model may fit the training data extremely closely while performing poorly on unseen data.

### Bias-Variance Trade-off

The project demonstrates how model complexity affects the balance between:

- **Bias** — error caused by an overly simple model
- **Variance** — sensitivity to the training data

---

## 🔬 Model Experiments

Polynomial Regression models with different degrees were compared:

| Degree | Purpose |
|--------|---------|
| **1** | Demonstrates underfitting |
| **3** | Captures a simple nonlinear trend |
| **9** | Captures more complex patterns |
| **20** | Demonstrates overfitting |

The experiments illustrate that increasing polynomial degree does not necessarily lead to better performance on unseen data.

---

## 📊 Dataset

The project uses historical **Delhi climate/temperature data**.

Time-related information, including **day of the year**, is used to capture seasonal temperature patterns.

---

## ⚙️ Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Preparation
   ↓
Chronological Train-Test Split
   ↓
Polynomial Feature Transformation
   ↓
Polynomial Regression
   ↓
Model Comparison
   ↓
Validation & Evaluation
   ↓
Final Model Selection
📈 Model Evaluation

The models are evaluated using three standard regression metrics.

RMSE — Root Mean Squared Error

Measures the magnitude of prediction errors while giving greater weight to larger errors.

MAE — Mean Absolute Error

Measures the average absolute difference between predicted and actual values.

R² Score

Measures how well the model explains the variation in the target variable.

🏆 Final Model Performance

The final held-out evaluation achieved approximately:

Metric	Result
RMSE	2.87°C
MAE	2.26°C
R² Score	0.79
💡 Key Findings
A low-degree polynomial can be too simple to capture the underlying temperature pattern.
Increasing polynomial complexity can improve the fit to training data.
Very high-degree polynomials can lead to overfitting.
Model performance should therefore be evaluated on unseen data rather than relying only on training performance.
Seasonal feature engineering can help capture recurring temperature patterns.
The project demonstrates the importance of selecting an appropriate level of model complexity.
🛠️ Technologies & Libraries
Language
Python
Libraries
NumPy
Pandas
Matplotlib
Scikit-learn
Environment
Jupyter Notebook
Google Colab
📂 Repository Structure
polynomial-curve-fitting-temperature-trends/
│
├── Polynomial_Curve_Fitting_Temperature_Trend.ipynb
└── README.md
📓 Notebook

The complete implementation, visualizations, experiments, and model evaluation are available in:

Polynomial_Curve_Fitting_Temperature_Trend.ipynb

📚 Skills Demonstrated
Python Programming
Data Preprocessing
Exploratory Data Analysis
Data Visualization
Feature Engineering
Polynomial Regression
Model Validation
Model Evaluation
Underfitting & Overfitting Analysis
Bias-Variance Trade-off
Regression Metrics
👩‍💻 Author

Akanksha Sharma

B.Tech — Computer Science Engineering (AI/ML)
