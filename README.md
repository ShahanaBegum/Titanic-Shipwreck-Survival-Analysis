# Titanic Shipwreck Survival Analysis with MLflow

## Overview

This repository contains code for building, logging, and tracking multiple versions of a classification model using MLflow. The objective is to predict the passengers who survived the Titanic shipwreck.

## Graded Assignment Details

- **Institution:** IIITs-Hyderabad
- **Course:** Data Ops, MLOps, AIOps
- **Assignment:** W2 - Data Ops, MLOps, AIOps Graded Assignment

## Dataset Description

The Titanic dataset is used for this analysis, containing information about passengers such as 'PassengerId', 'Name', 'Sex', 'Age', ticket class, fare, and survival status.

## Approach

1. **Data Preparation:**
   - Drop redundant columns.
   - Handle missing values.
   - Encode categorical variables.

2. **Model Training:**
   - Build a classification model using any algorithm learned in previous modules.

3. **MLflow Integration:**
   - Install MLflow and required libraries.
   - Log hyperparameters and evaluation metrics using MLflow.
   - Track and compare model performance using MLflow UI.

4. **Model Versioning:**
   - Make changes to the model training (e.g., hyperparameters, train size).
   - Train an updated model and track parameters for comparison.


## Steps

### 1. Install Dependencies

```bash
pip install -r requirements.txt

### 2. Data Preparation and Model Training
Refer to the Jupyter notebook (Titanic_Survival_Analysis.ipynb) for detailed steps on loading data, exploratory data analysis (EDA), and building the classification model.

### 3. MLflow Integration
Log hyperparameters, accuracy, precision, recall, and f1 score using MLflow.

### 4. Model Versioning and Comparison
Make changes to the model training.
Train an updated model and track parameters for comparison.S

