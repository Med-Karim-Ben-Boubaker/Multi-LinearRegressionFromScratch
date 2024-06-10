# Multi-Linear Regression from Scratch

## Introduction

In this notebook, we will explore the process of building a multi-linear regression model from scratch to predict movie revenue based on several features. We will start by exploring and cleaning the data, followed by data visualization and preprocessing. We will then dive into the details of constructing the model, training it using gradient descent, and finally evaluating its performance. Additionally, we'll implement an interactive visualization for gradient descent to better understand the optimization process.

## Table of Contents

1. **Exploring the Data**
   - Initial data examination
   - Summary statistics

2. **Data Cleaning**
   - Handling missing values

3. **Data Visualization**
   - Correlation matrix
   - Pair plots

4. **Data Preprocessing**
   - Feature scaling
   - Encoding categorical variables

5. **Multi Linear Regression Model from Scratch**
   - 5.1 **Model Description**
       - Understanding the model equation
   - 5.2 **Model Training**
       - 5.2.1 **Cost Function**
           - Derivation and explanation
   - 5.3 **Learning Algorithm: Gradient Descent**
       - 5.3.1 **Overview**
           - Basic concept and purpose
       - 5.3.2 **Calculating the Gradients for Weights**
           - Mathematical derivation
       - 5.3.3 **Calculating the Gradients for the Intercept**
           - Step-by-step calculation
   - 5.4 **Python Implementation**
       - Coding the model and training process

6. **Model Evaluation**
   - 6.1 **Mean Absolute Error**
       - Calculation and interpretation
   - 6.2 **Accuracy**
       - Metric definition and computation
   - 6.3 **Testing Our Model**
       - Performance on test data
   - 6.4 **Testing the Scikit-Learn Regression Model**
       - Comparison with our implementation
   - 6.5 **Actual Observation vs. Predicted Values**
       - Visual and numerical analysis
   - 6.6 **Regressions for Each Feature**
       - Individual feature impact analysis

7. **Interactive Gradient Descent Visualization for Linear Regression**
   - Dynamic visual representation of gradient descent

---