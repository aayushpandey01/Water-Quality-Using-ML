# 💧 Water Quality Checker

This project aims to check water quality using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), handling missing values, outlier treatment, and classification modeling to predict the safety of water samples.

## 📊 Problem Statement

Ensuring access to clean and safe drinking water is crucial. The dataset used contains various physicochemical features, and the target is to classify water samples as safe or not.

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn, feature_engine, imbalanced-learn, PyTorch
- **Models Used**: Random Forest, Gradient Boosting, and a Neural Network using PyTorch

## 🔍 Key Features

- Imputation of missing data using both sklearn and feature_engine pipelines.
- Outlier handling with Winsorization.
- Feature scaling and transformations.
- Resampling using `RandomUnderSampler` to handle class imbalance.
- Model training using:
  - Random Forest
  - Gradient Boosting Classifier
  - Feedforward Neural Network (PyTorch)
- Model evaluation with accuracy, confusion matrix, and classification report.

## 📁 Dataset

The dataset includes physicochemical parameters such as pH, conductivity, turbidity, and hardness, among others. Some columns contain missing values which are imputed during preprocessing.

## 📊 EDA Highlights

- Distribution plots, skewness and kurtosis analysis.
- Correlation matrix to analyze inter-feature relationships.
- Feature importance using permutation importance.

## 🔚 Conclusion

The best-performing model(s) can be deployed for practical water quality assessment. This pipeline is a scalable foundation for further deployment or integration with IoT systems.

