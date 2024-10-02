# Assignment 02: Learning from Data and Related Challenges & Classification



---

## Overview

This assignment focuses on the application of logistic regression for classification tasks and explores various challenges associated with learning from data. It includes tasks on data pre-processing, training logistic regression models, evaluating model performance, and understanding the impact of different solvers and feature scaling on classification accuracy.

---

## Contents

### 1. Logistic Regression

- **Data Preprocessing:**
  - Load the dataset and encode the categorical features.
  - Filter and clean the dataset to focus on specific classes (e.g., 'Adelie' and 'Chinstrap').

- **Training Logistic Regression Model:**
  - Train a logistic regression model using the **saga** solver.
  - Evaluate model performance and accuracy.

- **Changing Solvers:**
  - Switch the solver to **liblinear** and observe changes in classification accuracy.
  - Compare the performance of the **saga** and **liblinear** solvers with and without feature scaling.

- **Feature Scaling:**
  - Investigate the effect of standard scaling and min-max scaling on classification performance.

- **Handling Categorical Features:**
  - Analyze the correct approach for encoding and scaling categorical variables.

### 2. Logistic Regression on Real-World Data

- **Dataset Selection:**
  - Choose a dataset from the UCI Machine Learning Repository suitable for logistic regression.

- **Correlation and Pair Plot Analysis:**
  - Calculate the correlation matrix and create pair plots to analyze feature relationships.

- **Model Fitting:**
  - Fit a logistic regression model and evaluate its performance.

- **Feature Selection:**
  - Use **statsmodels.Logit** to interpret the p-values for each predictor and decide which features can be discarded.

### 3. Logistic Regression: First- and Second-Order Methods

- **Gradient Descent:**
  - Implement batch gradient descent and stochastic gradient descent to update model weights.
  - Analyze the loss function behavior over 20 iterations.

- **Newton’s Method:**
  - Implement Newton’s method for updating weights and compare its convergence with gradient descent methods.

- **Comparison of Optimization Methods:**
  - Compare the performance of batch gradient descent, stochastic gradient descent, and Newton’s method by plotting the loss function.

---

## Additional Resources

- [Scikit-learn Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/datasets)
- [Statsmodels Logit](https://www.statsmodels.org/stable/generated/statsmodels.discrete.discrete_model.Logit.html)

