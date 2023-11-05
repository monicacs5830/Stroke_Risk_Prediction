# Stroke Risk Prediction

## Introduction

Stroke, defined by a sudden loss of brain function, is a significant health concern worldwide, with symptoms that include facial drooping, confusion, vision loss, and severe headaches. According to the World Stroke Organization, about 12.2 million new stroke cases occur annually, with a mortality rate of nearly 50%. In Canada, stroke stands as the third leading cause of death and a leading cause of long-term disability. The multifactorial risk factors include hypertension, cardiovascular complications, lifestyle choices, and genetic predispositions. This project aims to understand these risk factors deeply, providing insights into modifiable aspects to potentially reduce stroke incidences.

## Objective

The objective of this R project is to analyze the "Stroke Prediction Dataset" from Kaggle to uncover significant contributing factors to stroke risks. Through examining demographic, lifestyle, and medical history data, we aim to develop a reliable predictive model for stroke occurrence. This model's predictions could help in assessing the future stroke risk in similar individuals.

## Dataset Overview

The "Stroke Prediction Dataset" includes health and lifestyle data from patients with a history of stroke. It consists of 5110 observations and 12 variables, including sex, age, medical history, work and marital status, residence type, and lifestyle habits. The dataset is available on Kaggle for educational and research purposes.

### Variables

- Categorical (Binary): sex, hypertension, heart_disease, ever_married, stroke
- Categorical (Multiple Categories): work_type, Residence_type, smoking_status
- Quantitative: id, age, avg_glucose_level, bmi

The response variable is 'stroke', with all others serving as explanatory variables.

## Methodology

Our approach involves:

- Data cleaning and transformation for analysis readiness.
- Sampling methods to ensure sample representativeness.
- Statistical techniques like generalized linear regression and Linear Discriminant Analysis (LDA) to estimate stroke probabilities.
- K-fold cross-validation to validate model robustness and accuracy.
- Decision tree analysis and comparisons with other techniques.
- Use of statistical tools such as contingency tables and varied link functions in generalized linear models.

## Conclusion

The Decision Tree model proved to be most effective for predicting stroke risk in this dataset, showing a low misclassification error rate and favorable cross-validation outcomes. Compared to other models like logistic regression and LDA, the Decision Tree's ability to handle diverse data types and outlier resilience made it the superior predictive model in this context.

