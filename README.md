# Titanic Shipwreck Survival Analysis with MLflow

## Overview
This repository contains code for building, logging, and tracking multiple versions of a classification model using MLflow. The objective is to predict the passengers who survived the Titanic shipwreck.

## Project Details
- **Institution:** International Institute of Information Technology (IIIT) Hyderabad
- **Author:** Shahana Begum

## Dataset Description
The Titanic dataset is used for this analysis, containing information about passengers such as 'PassengerId', 'Name', 'Sex', 'Age', ticket class, fare, and survival status.

## Approach

1. **Data Preparation:**
   - Drop redundant columns.
   - Handle missing values.
   - Encode categorical variables.

2. **Model Training:**
   - Refer to the Jupyter notebook (`Titanic_Survival_Analysis_Assignment.ipynb`) for detailed steps on loading data, exploratory data analysis (EDA), and building the classification model.

3. **MLflow Integration:**
   - Log hyperparameters, accuracy, precision, recall, and f1 score using MLflow.

4. **Model Versioning and Comparison:**
   - Make changes to the model training.
   - Train an updated model and track parameters for comparison.

## Steps

1. Install Dependencies
pip install -r requirements.txt

2.  Data Preparation and Model Training
Refer to the Jupyter notebook (Titanic_Survival_Analysis_Assignment.ipynb) for detailed steps on loading data, exploratory data analysis (EDA), and building the classification model.

3.  MLflow Integration
Log hyperparameters, accuracy, precision, recall, and f1 score using MLflow.

4. Model Versioning and Comparison
Make changes to the model training.
Train an updated model and track parameters for comparison.
