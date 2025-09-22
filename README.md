# Cardiovascular Disease Prediction Using Logistic Regression Model

Dataset used in this project can be found here: https://www.kaggle.com/datasets/christofel04/cardiovascular-study-dataset-predict-heart-disea/data

Project can be found here [M4S4_project1.ipynb](https://github.com/TuringCollegeSubmissions/gnaujo-PYDA.4.4/blob/main/M4S4_project1.ipynb)

**Goal** of this project was to develop a logistic regression model that helps predict the 10-year risk of CHD using relevant patient data.

**In order to succesfully reach the project's goal the following areas were adressed:**

1. Data preprocessing (handling missing values and identifying outliers).
2. Exploratory data analysis (understand variable distributions and potential risk factors).
3. Justified selection of variables to include in the model.
4. Spliting dataset into training and testing datasets.
5. Training a logistic regression model and evaluating its predictive performance.
6. Selecting appropriate classification metrics and determining the optimal decision threshold.

## Conclusion and Reccomendations
The developed Logistic Regression Model with an optimal decision threshold of 0.1752 demonstrates performance for predicting 10-year coronary heart disease (CHD) risk, where it correctly predicted **74%** of cases. The model successfully identified **61%** of individuals who actually developed CHD. This is especially important in clinical settings, where missing true positive cases could lead to delayed diagnosis and treatment. There is room for improvement and model's performance could be improved (61% of correctly identifying true CHD cases is still pretty low).

The following reccomendations suggest possible ways how the model could be improved:

1. Incorporate more features in to the model (that were not included), this could have an impact on the model's better performance.
2. Try other classification algorithms (Decision Trees)
3. Better asses outliers (discuss with medical professionals, look at outlier cases and treat them more carefully)
