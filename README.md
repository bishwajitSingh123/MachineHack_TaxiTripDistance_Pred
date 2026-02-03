🚕 Taxi Trip Distance Prediction

MachineHack Weekly Hackathon – Week 46
Rank: Top 14 on Leaderboard

📌 Problem Statement

Predict the trip distance (in miles) for taxi rides using historical taxi trip data.
This is a supervised regression problem evaluated using Root Mean Squared Error (RMSE).

The challenge was part of MachineHack’s Weekly Hackathon Series (Week 46), aimed at applying practical machine learning techniques to real-world tabular data.

🏆 Achievement

🥇 Top 14 Rank on MachineHack Leaderboard

📜 Participation Certificate from MachineHack

🚀 Intermediate-level ML competition with strong community participation

📊 Dataset Description

The dataset was provided by MachineHack and consists of:

train.csv – Taxi trip data with target variable trip_distance_miles

test.csv – Test set without target

submission.csv – Required submission format

⚠️ Note: Dataset files are not uploaded to this repository due to platform and licensing restrictions.
Dataset source: MachineHack platform (Taxi Trip Distance Prediction Challenge – Week 46)

⚙️ Approach & Methodology
1️⃣ Data Preprocessing

Handled missing values using statistical imputation

Removed irrelevant and leakage-prone columns

Feature type corrections and normalization where required

Exploratory Data Analysis (EDA) to understand feature distributions

2️⃣ Feature Engineering

Time-based feature extraction

Distance and location-based transformations

Categorical feature encoding

Outlier handling for extreme trip values

3️⃣ Model Development

Multiple regression models were explored and compared:

Linear & Ridge Regression

Random Forest Regressor

XGBoost

LightGBM

CatBoost Regressor (Final Model)

4️⃣ Training & Optimization

Cross-validation to ensure robustness

Hyperparameter tuning using:

RandomizedSearchCV

GridSearchCV

Metric optimization based on RMSE

5️⃣ Final Submission

Predictions generated on test set

Submitted in MachineHack-required format

Achieved Top 14 leaderboard position

📈 Evaluation Metric

RMSE (Root Mean Squared Error)
Lower RMSE indicates better prediction accuracy.

📁 Repository Structure
TaxiTrip
│── NYC_TaxiTrip_Prediction.ipynb
│── submission_catboost.csv
│── README.md

jupyter notebook NYC_TaxiTrip_Prediction.ipynb

🧠 Key Learnings

Effective feature engineering has a larger impact than model complexity

CatBoost performs exceptionally well on structured/tabular data

Cross-validation is essential for leaderboard stability

Clean pipelines matter in competitive ML

🧾 Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

CatBoost

Matplotlib / Seaborn

Jupyter Notebook

📌 Author

Bishwajit Singh
AI/ML Engineer | Computer Vision & Applied ML
🔗 Portfolio: https://bishwajitsingh123.github.io

🔗 LinkedIn: https://linkedin.com/in/bishwajitsingh

📢 Acknowledgements

MachineHack for organizing the Weekly Hackathon Series

Community members for discussions and insights
