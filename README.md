# SMOTE vs ADASYN Comparison for Diabetes Prediction

## Project Overview

In this project, we compare two oversampling techniques, **SMOTE** (Synthetic Minority Over-sampling Technique) and **ADASYN** (Adaptive Synthetic Sampling), for handling imbalanced datasets. We apply these techniques to a dataset obtained from [Kaggle - Predict Diabetes](https://www.kaggle.com/datasets/whenamancodes/predict-diabities) and use a **Support Vector Machine (SVM)** classifier to predict diabetes outcomes.

The primary goal of this project is to evaluate how well SMOTE and ADASYN perform in improving classification accuracy by addressing class imbalance, which is a common issue in medical prediction datasets.

## Dataset

The dataset used in this project is the **Pima Indians Diabetes Database**, which contains data on patients' medical records with the aim of predicting whether or not they have diabetes.

- **Dataset URL**: [Kaggle - Predict Diabetes](https://www.kaggle.com/datasets/whenamancodes/predict-diabities)

### Features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target variable:
- **Outcome**: 1 indicates the presence of diabetes, 0 indicates no diabetes.

## Techniques Used

1. **SMOTE (Synthetic Minority Over-sampling Technique)**:  
   SMOTE generates synthetic examples to balance the class distribution by creating new samples in the feature space.

2. **ADASYN (Adaptive Synthetic Sampling)**:  
   Similar to SMOTE, ADASYN generates synthetic data, but it focuses more on the minority class by generating more samples in areas where the data distribution is more complex.

3. **Support Vector Machine (SVM)**:  
   SVM is used as the classification model to predict diabetes based on the features provided in the dataset. The performance of SVM is evaluated before and after applying SMOTE and ADASYN.

