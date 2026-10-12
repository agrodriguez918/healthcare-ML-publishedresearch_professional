# healthcare-ML-publishedresearch_professional
Machine learning pipelines for chronic kidney disease and cardiovascular risk prediction using multi-year NHANES healthcare data, with comparative model evaluation and feature engineering.


# Ensemble Machine Learning for Healthcare Risk Prediction : A Comparative Analysis of Chronic Kidney Disease and Cardiovascular Risk Prediction with NHANES Data


# Overview

This research project investigates the application of statistical analysis and ensemble machine learning techniques to healthcare risk prediction using data from the National Health and Nutrition Examination Survey (NHANES), covering the 2017–March 2020 period. 
The study examines blood pressure control and its relationship with protein excretion, a clinical indicator relevant to chronic kidney disease (CKD) risk, among individuals with hypertension across demographic groups. It also investigates how machine learning can help analyze complex healthcare data and identify important predictors of health outcomes.
Using a sample of 666 participants, the project compares traditional statistical methods with ensemble learning approaches to evaluate predictive performance and explore demographic and clinical factors associated with cardiovascular health and CKD risk.


# Research Objectives

-  Investigate blood pressure control among hypertensive individuals across demographic groups.
- Examine the relationship between blood pressure history and protein excretion as a CKD-related risk factor.
- Compare traditional statistical techniques with machine learning approaches for healthcare outcome prediction.
- Evaluate ensemble learning strategies, including weighted ensembles and multi-meta stacking.
- Identify influential demographic and clinical predictors using feature importance analysis.
- Explore how predictive modeling can contribute to the analysis of healthcare disparities.

# Dataset

The study uses data from the National Health and Nutrition Examination Survey (NHANES), 2017–March 2020.
The analysis focuses on 666 participants and examines relevant demographic, clinical, and health-related variables.
The demographic groups examined include:

- Non-Hispanic Black individuals
- Hispanic individuals
- Mexican American individuals
- Non-Hispanic White individuals

The study considers blood pressure control among individuals with hypertension and examines protein excretion in relation to CKD risk.
NHANES is a publicly available survey program that collects health, nutrition, examination, and laboratory information to support population health research. 

# Methodology

The project combines traditional statistical analysis with machine learning to compare approaches to healthcare risk prediction.

# 1. Data Preparation and Feature Engineering


Healthcare survey data can present challenges involving missing values, class imbalance, and complex relationships between variables.
The analytical workflow addresses these challenges through data preparation and feature engineering to support statistical analysis and predictive modeling.

# 2. Statistical Analysis


Traditional statistical methods provide a baseline for examining relationships between variables and differences across groups.

# Methods include:

- Odds ratio analysis
- Hypothesis testing
- Examination of relationships between clinical and demographic variables

# 3. Ensemble Machine Learning

The study evaluates ensemble learning approaches for predicting healthcare outcomes.

The modeling strategies include:

- Weighted ensemble models
- Multi-meta stacking
- Comparative evaluation against individual classifiers

These methods combine predictions from multiple models to investigate whether ensemble approaches can improve predictive performance and balance across evaluation metrics.

# 4. Model Evaluation

Model performance is assessed using predictive evaluation metrics, including the area under the receiver operating characteristic curve (ROC-AUC).

The analysis also examines feature importance to identify demographic and clinical variables that contribute to model predictions.

# Key Findings

- Best reported AUC: 0.864. Ensemble methods achieved strong predictive discrimination in the evaluated prediction task.
- Blood pressure history emerged as the strongest predictor across models, highlighting its importance within the analyzed data.
- Ensemble methods improved predictive balance compared with individual classifiers, according to the study's evaluation.
- Feature importance analysis identified relevant demographic and clinical variables, providing additional insight into patterns associated with the modeled health outcomes.
- The comparison between statistical methods and machine learning demonstrates how complementary analytical approaches can be used to investigate complex healthcare datasets.

Note: The reported AUC reflects the evaluated modeling task and should not be interpreted as evidence of clinical validation or causal relationships.

# Technologies and Skills

Machine Learning: Ensemble learning, weighted ensembles, stacking
Statistical Analysis: Odds ratios, hypothesis testing
Data Science: Feature engineering, data preprocessing, predictive modeling
Model Evaluation: ROC-AUC, comparative model assessment, feature importance
Domain: Healthcare analytics, epidemiological survey data, health disparities research
Data Source: NHANES 2017–March 2020
