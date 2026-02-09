# Cardiovascular Disease Risk Prediction (Logistic Regression)

## Project Overview
This project develops a **logistic regression model** to estimate the 10-year risk of coronary heart disease (CHD) using patient health data. The objective is to support early risk identification, where failing to detect true CHD cases can have real world consequences.

Dataset: https://www.kaggle.com/datasets/christofel04/cardiovascular-study-dataset-predict-heart-disea/data
Project JupyterNotebook: [CHD_prediction.ipynb](https://github.com/G4bij4/logistic-regression-model-for-CHD-prediction/blob/main/CHD_prediction.ipynb)

## Objective
Build and evaluate a classification model that estimates CHD risk while prioritizing recall (sensitivity) to reduce the number of missed high-risk patients.

## Project Workflow
1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Model Development
5. Model Evaluation

## Model Performance
* Accuracy: 74%
* Recall (CHD cases detected): 61%

The model correctly identifies **61% of patients who developed CHD**, which is critical in healthcare contexts where false negatives can delay diagnosis and treatment.

## Interpretation and Limitations
While the model demonstrates reasonable performance, recall remains a limiting factor. In clinical applications, further improvements are needed to reduce missed CHD cases and increase reliability.

## Recommendations for Improvement
* Incorporate additional clinical features not included in the current dataset
* Experiment with alternative classification models (e.g. Decision Trees)
* Perform deeper outlier analysis in collaboration with medical experts
* Explore class imbalance handling techniques

als, look at outlier cases and treat them more carefully)
