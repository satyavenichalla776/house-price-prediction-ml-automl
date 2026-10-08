# House Price Prediction — Manual ML & Automated ML

## Project Overview

This project focuses on predicting house prices using two different Machine Learning approaches:

1. Manual Machine Learning using Scikit-learn
2. Automated Machine Learning using PyCaret

The main goal of the project was to understand the complete Machine Learning workflow manually and then compare it with an AutoML approach.

> Note: The Housing.csv dataset used in this project is a synthetic dataset created for learning and demonstration purposes.

---

## Dataset

The dataset contains 600 records and 13 columns.

### Features

- area
- bedrooms
- bathrooms
- stories
- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- parking
- prefarea
- furnishingstatus

### Target

- price

---

# 1. Manual Machine Learning

In the manual approach, I implemented the Machine Learning workflow step by step using Python and Scikit-learn.

### Workflow

```text
Load Dataset
     ↓
Data Exploration
     ↓
Data Preprocessing
     ↓
Categorical Encoding
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
     ↓
Cross-Validation
     ↓
Hyperparameter Tuning
     ↓
Final Model Selection