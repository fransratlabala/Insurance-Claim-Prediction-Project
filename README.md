# Insurance-Claim-Prediction-Project
End‑to‑end insurance claim prediction project: cleaned data, performed EDA to extract business insights, built baseline Logistic Regression, tuned with cross‑validation and GridSearch, evaluated with multiple metrics, and trained Random Forest for comparison to highlight trade‑offs in accuracy vs interpretability.

 Project Overview
This project explores an insurance dataset to understand client risk factors and predict claim likelihood. The workflow follows a complete data science pipeline:
- Data Cleaning – handled missing values, corrected data types, and ensured quality.
- Exploratory Data Analysis (EDA) – framed business questions (age, financial profile, vehicle info, risky behaviors, lifestyle, interactions) and answered them with claim‑rate analysis and visualizations.
- Baseline Modeling – trained a Logistic Regression model to establish a benchmark.
- Model Tuning – applied cross‑validation and GridSearchCV to optimize hyperparameters (regularization strength, penalty type, solver, class weights).
- Alternative Model – trained a Random Forest classifier, tuned its parameters, and compared performance with Logistic Regression.
- Evaluation – assessed models using accuracy, precision, recall, F1 score, and ROC‑AUC, with business framing (recall emphasized to catch risky clients).

⚙️ Methods
- Preprocessing: ColumnTransformer used to scale numeric features and encode categorical ones.
- Baseline Model: Logistic Regression with default parameters.
- Tuned Model: Logistic Regression with optimized hyperparameters via GridSearchCV.
- Extra Model: Random Forest classifier trained and tuned for comparison.
- Evaluation Metrics: Accuracy, precision, recall, F1 score, ROC‑AUC.

🎯 Business Insights
- Claims are relatively rare, but concentrated among specific high‑risk profiles.
- Younger drivers, high mileage, past accidents, and lower credit scores increase claim probability.
- Logistic Regression provides interpretability for underwriting decisions.
- Random Forest offers stronger predictive performance but less transparency.
- Trade‑off between recall (catching risky clients) and precision (avoiding false alarms) is highlighted for insurers.
