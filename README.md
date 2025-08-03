# 🗽 NYC Taxi Trip Duration Prediction

This machine learning project focuses on predicting taxi trip duration in New York City using a variety of preprocessing, feature engineering, and regularized regression techniques. The goal was to create a cleaner, more informative dataset and build an interpretable and robust predictive model.

## 📌 Project Overview

This project covers the end-to-end ML pipeline:
- Exploratory data analysis (EDA)
- Feature engineering and transformation
- Outlier detection and cleaning
- Custom transformers
- Hyperparameter tuning using cross-validation
- Model training and evaluation using `Ridge` and `Lasso` regression

## 🎯 Target Variable

- **Trip Duration** in seconds.

## 📊 Exploratory Data Analysis (EDA)

- Investigated relationships between features and the target variable.
- Identified and visualized trends across **days of the week** and **time of day**.
- Detected and removed **outliers** and **irrelevant data**.
- Analyzed linear dependencies between features to guide further engineering.

## 🧠 Feature Engineering

- Applied polynomial feature transformations where appropriate.
- Split composite features into smaller, more informative components.
- Combined linearly dependent features into unified representations.
- Developed a **custom scikit-learn transformer** to generate new features from existing ones.
- Cleaned and filtered features for model relevance and interpretability.

## 🛠 Modeling Pipeline

Built a full preprocessing and modeling pipeline using `scikit-learn`:
- Encapsulated feature transformations with `Pipeline`.
- Used `Ridge` and `Lasso` regression for modeling.
- Performed **cross-validation** to tune the `alpha` hyperparameter for `Ridge`.

## 🧪 Tools & Libraries

- Python
- NumPy / Pandas
- Matplotlib / Seaborn
- scikit-learn

## ✅ Results

- Boosted model effectiveness through intelligent feature engineering based on domain context.
- Enhanced generalization and interpretability using regularized regression and custom pipelines.
