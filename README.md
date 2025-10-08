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

```text
               precision    recall  f1-score   support
------------------------------------------------------
    Negative (0)       0.89      0.87      0.88       124
    Positive (1)       0.59      0.64      0.61        36
------------------------------------------------------
   weighted avg        0.82      0.82      0.82       160
```

## 🛠 Technologies Used
* **Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn, Imbalance-learn (SMOTE), XGBoost
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab
* **Deployment Potential:** Final model saved using `pickle` for future deployment.

## 🏃 Getting Started

To run this project locally and reproduce the results:

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository URL Here]
    ```
2.  **Open the Notebook:**
    * Open `Autism_Preidiction_using_machine_Learning.ipynb` in Google Colab, Jupyter, or VS Code.
3.  **Run Cells:**
    * Ensure all necessary Python libraries (listed above) are installed.
    * Execute the notebook cells sequentially to load the data, preprocess, train the models, and view the final results.

## Future Enhancements
* Deploy the final model as a simple web service (e.g., using Streamlit or Flask).
* Explore Deep Learning models (e.g., Neural Networks) to compare performance.
* Conduct more extensive Feature Engineering to potentially improve the F1-score for the positive class.
