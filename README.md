# adult-income-ml-classification
# Adult Income Prediction – Machine Learning Project

This repository contains a **machine learning model** that predicts whether an individual's annual income exceeds $50,000 based on census data from the UCI Adult dataset. The project follows a typical supervised learning workflow: preprocessing, model training, evaluation, and comparison.


## 📌 Problem Overview

The task is **binary classification** — predict if a person’s income is **>50K** (high income) or **≤50K** (low income) using demographic and employment features.  
This dataset is widely used in introductory ML tasks and real-world benchmarking.


## 📊 Dataset Details

The dataset contains demographic information such as:
- age
- workclass
- education
- marital status
- occupation
- relationship
- race
- sex
- capital gain / loss
- hours per week
- income label (target)

It is sourced from the **UCI Adult (Census Income) dataset**. 

## 🔍 Exploratory Data Analysis

Notebook includes:
- Handling of missing values  
- Encoding of categorical variables  
- Visualization of feature distributions  
- Observations about class imbalance and feature relationships



## 🧠 Models Trained

At minimum, the following models were trained:

| Model | Description |
|-------|-------------|
| Logistic Regression | Linear baseline classifier |
| Random Forest        | Tree-based ensemble model |
| (Your choice)        | Additional model you selected |

For each model, key performance metrics were recorded.

## 📈 Model Evaluation

Metrics used:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**
- **ROC-AUC**

This gives a balanced view of model performance beyond simple accuracy.



