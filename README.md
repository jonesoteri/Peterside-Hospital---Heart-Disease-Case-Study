# Peterside-Hospital---Heart-Disease-Case-Study

## Table of Contents 
- [Project Objective](#project-objective).
- [Data Sources](#data-sources).
- [Data Preprocessing](#data-preprocessing).
- [Exploratory Data Analysis](#EDA).
- [Machine Learning Model](#machine-learning-model).
- [Evaluation Metrics](#evaluation-metrics).
- [Key_Insights](#key-insights).
- [Conclusion](#conclusion)

## Project Objective
The project aim to develop a machine-learning model for predicting the likelihood of a person having a heart disease based on there health features.

## Data Sources
The Dataset used in these project was provided by 10Alytics. The dataset contains relevant health data from patients at Peterside Hospital, including demographic information, medical history, lifestyle factors and results from diagnostic test.

## Data Preprocessing
Before feeding the data into the machine learning model, extensive data preprocessing was performed. This include handling missing values, outliers and inconsistencies. This steps involves feature engineering, normalization and encoding categorical variables.

## Exploratory Data Analysis 
Ranging from Univariate, Bivariate and Multivariate data analysis was performed to gain insights into the relationships between features and there impact on heart disease risk. This steps helps identify patterns, correlations and potential predictive variables.

## Machine Learning Model
The heart disease model was built using a supervised machine learning approach. Training and test data was split 80:20. Several  classsification algorithm were experimented with

- **Logistic Regression**
- **Random Forest Classifier**
- **K-Nearest Neighbours**
- **Decision Trees**

After extensive experimentaion and hyperparameter tuning, the final machine learning model was selected based on the performance and generalization capabilities.

## Evaluation Metrics
To access the performance of machine learning model, the following evaluation metrics were used:
- **Accuracy (0.852):** This indicates the proportion of correctly classified case of heart disease patient in the test data. In this case, 85.2% of the predictions were accurate.
- **Precision (0.871):** This measures the proportion of positive predictions that were actually correct (correctly identified cases of heart disease patient).
- **Recall (0.844):** This measures the proportion of actual heart disease cases that were correctly identified by the model.
- **F1-score (0.857):** This combines precision and recall into a single metric, providing a balanced view of the model's performance.
- **AUC-ROC (0.853):** This metric reflects the model's ability to distinguish between healthy and heart disease cases.

## key Insights
- This project tackles a crucial problem in healthcare - predicting the likelihood of heart disease. By developing a machine learning model, aiming to leverage data to potentially improve preventive measures and early detection.
- The best model that predicts with lesser error is to be chosen, however subjecting them to different evaluation metrics including k-fold cross validation.
- The confusion matrix displays the error value for each model in terms of false negative (where the model predict that there are 0 patient with heart disease but on the actual there are 5 patient with heart disease.

  ## Conclusion
  The "Peterside-Hospital---Heart-Disease-Case project" i successfully developed a machine learning       model for predicting the likelihood of heart disease using a supervised learning approach.
  The RandomForestClassifier has highest of recall score 87.2% compare to other models, along with good   precision, recall, F1-score, and AUC-ROC, indicating its effectiveness in identifying heart disease     cases.


