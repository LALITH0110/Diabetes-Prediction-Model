# CSP-571-Summer
This project focuses on building interpretable and reliable models for predicting diabetes using structured health data. We integrate multiple datasets — including the Diabetes Prediction Dataset from Kaggle, the Pima Indians Diabetes Dataset — to explore key risk factors and develop robust machine learning models.


## Overview of `diabetes_prediction_dataset.Rmd`

This file performs a comprehensive preprocessing and analysis of the **Diabetes Prediction Dataset**. The operations include:

- Data cleaning and deduplication  
- Exploration and visualization of feature relationships  
- Feature selection and transformation  
- Encoding of categorical variables (e.g., gender, smoking history)

In addition to preprocessing, this file applies and compares several machine learning models for predicting diabetes, including:

- **Generalized Linear Model (GLM)**  
- **Random Forest**  
- **Extreme Gradient Boosting (XGBoost)**

These models are evaluated to identify key predictive factors and to assess model performance in terms of accuracy, F1 score, and interpretability.

## Overview of `Pima_Indians_Diabetes.Rmd`

This file focuses on preprocessing, exploring, and modeling the **Pima Indians Diabetes Dataset**. The workflow includes:

* **Data loading and cleaning** – handling missing values and biologically implausible zeros, imputing data, and removing duplicates.
* **Exploratory data analysis** – visualizing distributions, feature-target relationships, and correlations (e.g., age vs. glucose, pregnancy count vs. diabetes status).
* **Feature engineering** – creating interaction terms (e.g., glucose × BMI), grouping continuous variables into categories (age, glucose, BMI), and scaling numeric features.
* **Model training and evaluation** – applying Logistic Regression (GLM), Random Forest, and XGBoost with cross-validation and hyperparameter tuning, comparing performance on accuracy, F1 score, ROC AUC, and feature importance.
* **Model interpretation** – identifying key predictors and discussing the significance of each feature in relation to diabetes risk.


## Project File Descriptions

* **CSP-571\_summer\_presentation.mp4**
  A recorded project presentation video. Summarizes the objectives, datasets, methodology, model comparisons, evaluation metrics, and key findings in a concise and visual format.

* **Pima\_Indians\_Diabetes.Rmd**
  R Markdown file for processing and analyzing the Pima Indians Diabetes Dataset. Includes data cleaning, feature engineering, exploratory data analysis, multiple model training (GLM, Random Forest, XGBoost), evaluation, and interpretation.

* **diabetes\_prediction\_dataset.Rmd**
  R Markdown file for processing and analyzing the Diabetes Prediction Dataset from Kaggle. Includes data preprocessing, feature encoding, visualization, and model comparison (GLM, Random Forest, XGBoost) with performance evaluation.

* **diabetes\_prediction\_dataset.csv**
  The structured CSV dataset file used in `diabetes_prediction_dataset.Rmd`. Contains health-related features and the diabetes label for predictive modeling.

* **extra.Rmd**
  An additional R Markdown file containing supplementary analyses beyond the main two datasets. Includes Principal Component Analysis (PCA) for dimensionality reduction and clustering analysis to explore hidden patterns and groupings in the data.

