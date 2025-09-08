# Foundational Machine Learning Projects

This repository contains my practice work with fundamental machine learning models on datasets from Kaggle. These notebooks demonstrate a full workflow, from data ingestion and cleaning to model training, evaluation, and tuning.

---
### 1. Salary Prediction with Linear Regression
* **[View Notebook](./Linear_Regression.ipynb)**
* **Objective:** To predict salary based on years of experience using various linear regression techniques.
* **Dataset:** "Salary Data for ML Code-a-thon" on Kaggle.
* **Skills Demonstrated:**
    * **Model Training:** Implemented `LinearRegression`, `Ridge` (for regularization), and `Lasso` (for feature selection).
    * **Model Evaluation:** Calculated R-squared and Root Mean Squared Error (RMSE) to measure performance.
    * **Validation:** Used K-Fold Cross-Validation to ensure the model's robustness and prevent overfitting.
    * **Visualization:** Plotted regression lines against test data using Matplotlib to visualize model predictions.

---
### 2. Maternal Health Risk Classification
* **[View Notebook](./Logistic_Regression.ipynb)**
* **Objective:** To build and evaluate several classification models to predict the level of risk in maternal health based on biometric data.
* **Dataset:** "ML Olympiad Bangladesh 2025" on Kaggle.
* **Skills Demonstrated:**
    * **Preprocessing:** Scaled numerical features using `StandardScaler`.
    * **Model Training:** Implemented `LogisticRegression`, `KNeighborsClassifier` (KNN), and `DecisionTreeClassifier`.
    * **Pipelines:** Built end-to-end machine learning pipelines to streamline the process of imputation, scaling, and classification.
    * **Hyperparameter Tuning:** Used `GridSearchCV` to systematically find the optimal parameters for the logistic regression model.
    * **Advanced Evaluation:** Generated Confusion Matrices, Classification Reports, and plotted a multi-class **ROC curve with AUC scores** to provide a comprehensive view of model performance.
