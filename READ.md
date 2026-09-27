# Diabetes Prediction using Decision Tree 🩺📊 
http://localhost:8888/notebooks/Diabetes%20Prediction%20using%20Decision%20Tree.ipynb


## Overview

This project analyses the factors associated with diabetes and uses a Decision Tree Classifier to predict whether an individual is likely to have diabetes based on different health-related features.

## Objective

The main objective is to explore the dataset, understand the relationship between different health indicators and diabetes outcome, and build a Decision Tree classification model.

The analysis focuses on:

- Understanding the dataset and its variables.
- Exploring distributions and relationships between features.
- Examining correlations between health indicators.
- Identifying differences between diabetic and non-diabetic outcomes.
- Building a Decision Tree model for diabetes classification.

## Dataset

The dataset contains **768 observations and 9 variables**, including:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

Some variables contain zero values that may represent missing or unavailable measurements, particularly Glucose, BloodPressure, SkinThickness, Insulin, and BMI. :contentReference[oaicite:1]{index=1}

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Exploratory Data Analysis

The project uses:

- Pair plots
- Correlation heatmap
- Distribution plots
- Boxplots

These visualizations are used to understand the distributions of the variables and examine their relationship with diabetes outcome. :contentReference[oaicite:2]{index=2}

## Decision Tree Model

A Decision Tree Classifier was trained using the available health-related features to classify individuals into diabetic and non-diabetic categories.

The model achieved an accuracy of approximately **74.7%** on the test data, with the confusion matrix showing **75 true negatives, 24 false positives, 15 false negatives, and 40 true positives**. :contentReference[oaicite:3]{index=3}

The decision tree was also visualized to understand the rules used by the model for classification.

## Conclusion

This project demonstrates how exploratory data analysis and Decision Tree classification can be used to study diabetes-related patterns and build a basic predictive model.

The analysis also highlights the importance of careful data handling, model interpretation, and human validation when applying machine learning in healthcare settings. :contentReference[oaicite:4]{index=4}

## Future Scope

The project can be extended by:

- Handling zero values as potential missing observations.
- Comparing different classification algorithms.
- Applying feature selection and hyperparameter tuning.
- Evaluating the model using additional classification metrics.
- Improving model performance and interpretability.

## Author

**Shreya Kispotta**
