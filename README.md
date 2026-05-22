<div align="center">

# Multiple Linear Regression for House Price Prediction

### Predicting House Prices Using Area and Bedrooms with Data Preprocessing, Correlation Analysis, and Regression Modeling

</div>

---

# Repository Overview

This project demonstrates the implementation of the **Multiple Linear Regression Algorithm** using a custom house pricing dataset created in CSV format.  

The project focuses on understanding how multiple independent variables influence a target variable and how machine learning models learn relationships from real-world structured data.

Unlike simple regression where only one feature is used, this project explores prediction using multiple features together, making the workflow closer to practical machine learning applications.

In addition to coding implementation, handwritten mathematical intuition and manual calculations of regression concepts are also included in PDF format to strengthen conceptual understanding.

---

# Problem Statement

Can house prices be predicted using multiple property features such as area and number of bedrooms?

This project explores how Multiple Linear Regression identifies relationships between several independent variables and generates predictions using a mathematical best-fit model.

---

# Dataset Information

A small custom CSV dataset was created containing:

| Feature | Description |
|---|---|
| Area | Size of the house |
| Bedrooms | Number of bedrooms |
| Price | House price (Target Variable) |

The dataset was loaded using Pandas for preprocessing and machine learning implementation.

---

# Project Workflow

## 1. CSV Dataset Creation
A custom dataset was manually created and stored in CSV format to simulate real-world housing data.

---

## 2. Data Loading & Exploration
The dataset was loaded using Pandas and analyzed to inspect:
- Data structure
- Missing values
- Feature relationships
- Numerical distributions

---

## 3. Data Preprocessing
The dataset contained missing values which were identified and handled before model training.

Preprocessing tasks included:
- Detecting null values
- Filling missing values using mean values
- Preparing features for model training

---

## 4. Correlation Analysis
Feature relationships were analyzed using correlation methods to understand:
- How features relate to house prices
- Strength of relationships between variables
- Impact of multiple inputs on predictions

---

## 5. Data Visualization
Several visualizations were created including:
- Scatter plots
- Feature relationship analysis
- Regression visual representation

The project also explores the challenge of visualizing Multiple Linear Regression where multiple features create zigzag prediction behavior instead of a perfectly straight regression line.

---

## 6. Model Training
The Multiple Linear Regression model was trained using:
- Area
- Bedrooms

to predict:
- House Price

The project includes:
- Train-test splitting
- Model fitting
- Prediction generation

---

## 7. Prediction Analysis
After training, predictions were generated and compared with actual values to evaluate model behavior.

To better visualize predictions, additional scatter plots were created comparing:
- Actual values
- Predicted values

This approach provided clearer insight into model performance compared to traditional regression line visualization.

---

## 8. Handwritten Mathematical Intuition
Alongside the coding implementation, handwritten notes and manual calculations were created to understand:
- Slope (m)
- Intercept (b)
- Regression intuition
- Best-fit line concepts

The handwritten explanation PDF is included in the repository.

---

# Output of the Project

The trained model successfully:
- Learned relationships between multiple housing features
- Predicted house prices using regression analysis
- Demonstrated preprocessing workflows
- Visualized actual vs predicted results
- Highlighted real-world challenges of Multiple Linear Regression visualization

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Scikit-learn | Machine Learning Model |

---

# Learning Objective

This project was developed to strengthen understanding of:
- Multiple Linear Regression
- Data preprocessing
- Missing value handling
- Correlation analysis
- Feature relationships
- Prediction systems
- Regression visualization challenges

The repository combines theoretical intuition, handwritten mathematical understanding, and practical machine learning implementation to build a strong foundation in regression modeling.

---

<div align="center">

### Repository Includes

CSV Dataset • Data Preprocessing • Correlation Analysis • Scatter Plot Visualization • Multiple Linear Regression • Prediction Analysis • Actual vs Predicted Comparison • Handwritten Regression Intuition PDF

</div>
