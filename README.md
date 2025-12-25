# ML_Projects

Adult Census Income Prediction Project

Project Overview

This project aims to predict whether an individual's annual income exceeds $50,000 based on demographic and employment attributes. This is a classic binary classification problem using the Adult Census Income dataset, a popular dataset sourced from the UCI Machine Learning Repository and widely available on Kaggle.

Problem Statement

The goal is to analyze personal data (such as age, education, marital status, and occupation) to determine if a person is likely to earn more than $50k per year. This information can be useful for social studies, economic policy planning, and targeted marketing.

Features & Methodology

1.To ensure high-quality results and professional code standards, the project utilizes:

2.Scikit-learn Pipelines: Automates the workflow and prevents data leakage by keeping training and testing data strictly separate during preprocessing.

3.ColumnTransformer: Handles mixed data types by applying different transformations to numerical and categorical features simultaneously.

 Preprocessing Steps:

 1.Numerical Processing: Missing values are handled via Median Imputation, followed by Standard Scaling to normalize feature ranges.

 2.Categorical Processing: Missing values are handled via Mode Imputation (most frequent), followed by One-Hot Encoding to convert text to numerical binary columns.

Machine Learning Models

We compared two distinct types of machine learning models to identify the most effective approach:

1.Logistic Regression (Linear Model): A baseline linear classifier that is highly interpretable and efficient for binary tasks.

2.Decision Tree Classifier (Non-Linear Model): A tree-based model that captures complex, non-linear relationships and interactions between features.
