# BigMart Sales Prediction

A Machine Learning project that predicts product sales for BigMart outlets using product and outlet information. The project focuses on data preprocessing, feature engineering, model comparison, and improving prediction performance using ensemble learning techniques.

## Features
- Data preprocessing and cleaning
- Missing value imputation
- Feature engineering
- Categorical feature encoding
- Comparison of multiple regression models
- Sales prediction using ensemble learning

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- Matplotlib
- Seaborn

## Machine Learning Concepts Used
- Data Preprocessing
- Missing Value Imputation
- Feature Engineering
- Categorical Encoding
- Regression
- Train-Test Split
- Model Evaluation
- Ensemble Learning

## Models Implemented
- XGBoost Regressor
- CatBoost Regressor

The performance of multiple regression models was compared. CatBoost achieved better generalization by reducing the gap between training and testing performance, making it the final selected model.

## Dataset
big_mart_data dataset

The dataset contains product and outlet information, including:

- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Size
- Outlet Location Type
- Outlet Type
- Outlet Establishment Year
- Item_Outlet_Sales

## Project Workflow
1. Load and explore the dataset.
2. Handle missing values.
3. Perform feature engineering.
4. Encode categorical variables.
5. Train multiple regression models.
6. Compare model performance.
7. Select the best-performing model.
8. Predict product sales.

## Results
Multiple regression algorithms were evaluated for sales prediction. CatBoost Regressor achieved the best balance between training and testing performance, making it the final model for prediction.

## Future Improvements
- Perform hyperparameter tuning for CatBoost.
- Deploy the model.
- Build an interactive dashboard for sales prediction.

## Author
Sushant Ratawa
