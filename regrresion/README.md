# Regression Midterm

## Project Overview
This project aims to build an end-to-end machine learning regression pipeline to predict continuous target values using song/audio feature datasets.

The workflow includes:
- Data preprocessing
- Missing value handling
- Outlier removal
- Feature selection
- Feature scaling
- Model training
- Hyperparameter tuning using Optuna
- MLflow experiment tracking
- Model interpretability using LIME

---

# Dataset

Dataset used:
- `midterm-regresi-dataset.csv`

The first column represents the target variable (song release year), while the remaining columns are numerical audio features.

---

# Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

# Workflow

1. Dataset Loading
2. Exploratory Data Analysis (EDA)
3. Missing Value Handling
4. Outlier Removal
5. Feature Selection
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Hyperparameter Tuning using Optuna
11. MLflow Experiment Tracking
12. LIME Interpretability
13. Conclusion

---

# Evaluation Metrics

- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

---

# Best Model Result

XGBoost achieved the best regression performance.

## Results
- RMSE: 6.38
- MAE: 4.78
- R² Score: 0.38

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Optuna
- MLflow
- LIME
- Google Colab

---

# Author

Sulthon Arif Imadudin  
NIM: 1103223206
