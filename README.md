# KagglePro: Data Science Showcase

[Repository Link](https://github.com/thekazisakib/KagglePro-Data-Science-Showcase.git)

## Overview

This repository consolidates a series of data science projects based on popular Kaggle datasets, showcasing skills in exploratory data analysis (EDA), feature engineering, machine learning, and model evaluation. Each project addresses a unique business problem, providing valuable insights and predictive solutions. This portfolio demonstrates proficiency in various domains, from image analysis to survival prediction and price estimation, making it an excellent resource for potential data science roles.

## Table of Contents

- [Projects](#projects)
  - [1. Advanced House Price Prediction](#1-advanced-house-price-prediction)
  - [2. Decode Digits: ML for Image Analysis](#2-decode-digits-ml-for-image-analysis)
  - [3. Titanic ML Mastery: Predicting Survival Swiftly](#3-titanic-ml-mastery-predicting-survival-swiftly)
- [Skills Demonstrated](#skills-demonstrated)
- [Installation](#installation)
- [Conclusion](#conclusion)

---

## Projects

### 1. Advanced House Price Prediction

**Notebook**: [advanced-house-price-prediction.ipynb](https://github.com/thekazisakib/KagglePro-Data-Science-Showcase/blob/main/advanced-house-price-prediction.ipynb)

**Objective**: Predict house prices in Ames, Iowa, using a variety of predictive features related to property characteristics, neighborhood, and market conditions.

**Key Steps**:
- **EDA and Data Cleaning**: Performed extensive feature exploration and handled missing values, outliers, and skewed distributions.
- **Feature Engineering**: Created new variables like `TotalSF` and `OverallQual`, which demonstrated significant correlations with sale prices.
- **Modeling**: Implemented multiple regression models, including Lasso and Ridge Regression, achieving an optimal blend of accuracy and interpretability.
- **Performance**: Achieved a high R-squared score and low RMSE, indicating model precision and robust predictions.

**Business Impact**: Provides real estate agents and property developers with accurate price estimations, assisting in better pricing strategies and investment decisions.

---

### 2. Decode Digits: ML for Image Analysis

**Notebook**: [decode-digits-ml-image-analysis.ipynb](https://github.com/thekazisakib/KagglePro-Data-Science-Showcase/blob/main/decode-digits-ml-image-analysis.ipynb)

**Objective**: Classify handwritten digits using machine learning techniques on image data from the MNIST dataset.

**Key Steps**:
- **Data Preprocessing**: Applied normalization and reshaped the data to prepare it for machine learning.
- **Model Selection**: Used Convolutional Neural Networks (CNN) due to their effectiveness in image processing, with multiple convolutional and pooling layers to capture patterns.
- **Evaluation**: Achieved over 98% accuracy, with strong performance across different digit classes.

**Business Impact**: Demonstrates the use of ML in automated image recognition tasks, applicable in fields like OCR, document processing, and visual authentication.

---

### 3. Titanic ML Mastery: Predicting Survival Swiftly

**Notebook**: [titanic-ml-mastery-predicting-survival-swiftly.ipynb](https://github.com/thekazisakib/KagglePro-Data-Science-Showcase/blob/main/titanic-ml-mastery-predicting-survival-swiftly.ipynb)

**Objective**: Predict passenger survival based on features like age, gender, and passenger class from the famous Titanic dataset.

**Key Steps**:
- **EDA and Visualization**: Explored survival distribution by features to uncover key factors influencing survival.
- **Feature Engineering**: Created binary and polynomial features to capture interactions between variables like `Pclass`, `Sex`, and `SibSp`.
- **Modeling and Hyperparameter Tuning**: Employed Random Forest and Gradient Boosting classifiers, optimizing hyperparameters for higher accuracy.
- **Results**: Achieved a high accuracy score, with model insights that aligned well with historical survival trends.

**Business Impact**: Offers insight into predictive modeling for risk assessment and decision-making in scenarios involving human factors and resources.

---

## Skills Demonstrated

- **Data Wrangling and Preprocessing**: Handling missing values, outlier treatment, data scaling, and transformations.
- **Feature Engineering**: Extracting new features and combining existing ones to maximize model performance.
- **Model Development**: Proficiency in a range of machine learning models, including linear regression, decision trees, random forests, gradient boosting, and CNNs.
- **Hyperparameter Tuning**: Applying GridSearchCV and other techniques for model optimization.
- **Evaluation Metrics**: Familiarity with RMSE, accuracy, precision, recall, and AUC-ROC to measure and validate model effectiveness.

---

## Installation

To explore the projects locally, clone the repository and ensure the required dependencies are installed.

```bash
# Clone this repository
git clone https://github.com/thekazisakib/KagglePro-Data-Science-Showcase.git

# Navigate to the project directory
cd KagglePro-Data-Science-Showcase

# Install dependencies
pip install -r requirements.txt
```

Each project notebook can be run independently in a Jupyter Notebook environment.

---

## Conclusion

This repository showcases a diverse skill set in data science and machine learning, emphasizing real-world problem-solving and technical proficiency across various domains. These projects demonstrate a thorough understanding of the data science pipeline, from EDA and feature engineering to model deployment and business impact, positioning me as a strong candidate for data science roles.

