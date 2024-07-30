This project aims to detect fraudulent credit card transactions using a machine learning approach. We employ the Logistic Regression algorithm to classify transactions as either fraudulent or legitimate.

Dataset Link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Dataset : The dataset used in this project is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions. It contains 31 features, including Time, Amount, and Class, where Class is the target variable indicating the transaction's authenticity (0 for legitimate, 1 for fraudulent).

Key Steps
Data Preprocessing: Handling missing values, scaling numerical features, and addressing data imbalance using techniques like oversampling and undersampling.
Exploratory Data Analysis (EDA): Analyzing the distribution of features and identifying patterns associated with fraudulent transactions.
Feature Engineering: Creating new features or transforming existing ones to improve model performance.
Model Training: Training a Logistic Regression model on the preprocessed dataset.
Model Evaluation: Assessing the model's performance using metrics such as accuracy, precision, recall, F1-score, and the ROC-AUC score.
Prediction: Applying the trained model to predict the authenticity of new transactions.
