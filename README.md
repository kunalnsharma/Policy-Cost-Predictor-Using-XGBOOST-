# Policy-Cost-Predictor-Using-XGBOOST-
🚗 Insurance Policy Cost Prediction using XGBoost Regressor
This project focuses on predicting the Policy Cost (insurance premium amount) for customers based on anonymized customer attributes using XGBoost Regressor, a powerful gradient boosting machine learning algorithm.

📁 Dataset Overview
The dataset consists of three files:

train.csv — Contains features and the target variable Policy Cost for training.

x_test.csv — Contains only features; used for making final predictions.

sample_submission.csv — A template showing the expected format for the submission.

🧾 Features Description
Although the columns are anonymized, here's a summary of the types of data present:

Numerical Features: Years Lived, Yearly Earnings, Dependent Count, Prior Claims, Automobile Age, Financial Rating, etc.

Categorical Features: Sex, Relationship Status, Academic Standing, Job Title, Region, Coverage Class, Client Review, Tobacco Use, Physical Activity, Asset Category, etc.

Date/Time Feature: Coverage Commencement

Target Variable: Policy Cost (only in train.csv)

🛠️ Preprocessing Steps
Missing value handling using appropriate imputers.

Encoding of categorical features using OneHotEncoding or LabelEncoding.

Conversion of date column Coverage Commencement into datetime and extraction of relevant components (like year, month).

Feature scaling for numerical variables (if necessary for model performance).

🚀 Model Used
XGBoost Regressor:

Handles both numerical and categorical features efficiently.

Robust to overfitting due to regularization.

Hyperparameter-tuned (basic/default configuration in this version).
