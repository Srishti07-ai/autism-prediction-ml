# 🧠 Autism Spectrum Disorder (ASD) Prediction using Ensemble Machine Learning

## Project Goal
This project aims to develop a robust, high-performance Machine Learning model for the early prediction and risk assessment of **Autism Spectrum Disorder (ASD)** based on diagnostic screening features.

## Key Features and Technical Highlights
This project showcases an end-to-end ML pipeline, demonstrating proficiency in data manipulation, model selection, and performance optimization on a real-world classification problem.

| Feature | Technical Skill Demonstrated |
| :--- | :--- |
| **Imbalanced Data Handling** | Utilized **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the highly skewed dataset, preventing bias toward the majority class. |
| **Advanced Modeling** | Implemented and optimized an **Ensemble Classifier** (XGBoost and Random Forest) for superior predictive power and stability. |
| **Model Optimization** | Employed **RandomizedSearchCV** for efficient **Hyperparameter Tuning** to find the optimal configuration for the best performing model. |
| **Code Structure** | Full pipeline contained in a single, well-documented Jupyter Notebook (`Autism_Prediction_using_machine_Learning.ipynb`). |

## 🎯 Final Model Performance

The best-performing model was selected based on a comprehensive evaluation of classification metrics on the test set:

| Metric | Result |
| :--- | :--- |
| **Weighted Accuracy** | **82%** |
| **Macro Average F1-Score** | **0.75** |
| **True Positives (Sensitivity/Recall for Class 1)** | **64%** |
| **Model Used** | **XGBClassifier (Best Performing)** |

**Classification Report Summary:**
