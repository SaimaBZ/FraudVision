# FraudVision

This project aims to develop a machine learning model to detect fraudulent credit card transactions in real-time. Utilizing a dataset containing 31 features and a class label, the project focuses on identifying patterns that differentiate fraudulent transactions from legitimate ones. The dataset includes a "Time" feature, 28 anonymized PCA-transformed features (V1 to V28), the "Amount" feature representing the transaction amount in USD, and a "Class" label indicating fraud.

Several machine learning models were trained, including Logistic Regression, Random Forest, and XGBoost. Cross-validation and hyperparameter tuning were employed to optimize the models and ensure robust performance.

The models were evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. The Random Forest model achieved the highest performance, with an F1-score of 0.95 and an ROC-AUC of 0.98 on the test set.

The best-performing model was deployed using Streamlit, resulting in an interactive web application. This app allows users to input transaction details and receive immediate predictions on whether the transaction is fraudulent.
