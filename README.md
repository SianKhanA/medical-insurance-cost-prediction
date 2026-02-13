# Medical Insurance Cost Prediction

## Project Overview
This project predicts individual medical insurance costs using patient data. I implemented a full Machine Learning pipeline, improving the baseline model performance by ~89% through feature engineering and hyperparameter tuning.

## Key Technical Achievements
* **Feature Engineering:** Implemented Degree-2 Polynomial features to capture non-linear interactions between variables like BMI and Smoking status.
* **Regularization:** Utilized **Elastic Net (Lasso/Ridge)** to perform automatic feature selection, effectively reducing model complexity and preventing overfitting.
* **Optimization:** Used **GridSearchCV** with 5-fold cross-validation to find optimal hyperparameters ($\alpha=31$, $L1\_ratio=1$).
* **Evaluation:** Reduced Mean Absolute Error (MAE) from a baseline of ~$27k down to **$3,104**.

## Technologies Used
* Python, Pandas, Scikit-Learn
* Matplotlib & Seaborn for Residual Analysis
