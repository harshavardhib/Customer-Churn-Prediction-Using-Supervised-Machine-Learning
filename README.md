# Customer-Churn-Prediction-Using-Supervised-Machine-Learning
Machine Learning project for predicting customer churn in the telecommunications industry using supervised learning techniques such as Logistic Regression, Decision Tree, Random Forest, and SVM.
Project Overview
Customer churn prediction is an important challenge in the telecommunications industry because retaining existing customers is often more cost-effective than acquiring new ones. This project applies supervised machine learning techniques to predict customer churn using the Telco Customer Churn dataset. Multiple classification algorithms were implemented and compared to determine the most effective predictive model. The objective of this project is to identify customers likely to discontinue telecommunication services and help organizations implement proactive customer retention strategies.
Dataset Information
Dataset Name: Telco Customer Churn Dataset
Source: Kaggle
Dataset Link:https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download
The dataset contains 7,043 customer records and 21 variables, including customer demographics, subscription details, billing information, and service usage patterns.
Target Variable: Churn (Yes / No)
Technologies Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Jupyter Notebook / Google Colab
Machine Learning Models Implemented
The following supervised learning algorithms were implemented and evaluated: Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), Data Preprocessing

Several preprocessing techniques were applied to improve model performance:
Missing value handling
Conversion of categorical variables into numerical format
Label Encoding
Removal of unnecessary features (customerID)
Train-test split (80:20 ratio)
Evaluation Metrics

The models were evaluated using the following performance metrics:
Accuracy Score
Precision
Recall
F1-score
ROC-AUC Score
Confusion Matrix
Project Results
Model	Accuracy	ROC-AUC
Logistic Regression	81.62%	86.15%
Random Forest	78.92%	83.58%
SVM	73.53%	81.66%
Decision Tree	72.81%	65.90%
Best Performing Model: Logistic Regression achieved the highest predictive performance with an accuracy of 81.62% and ROC-AUC score of 86.15%, making it the most effective model for customer churn prediction in this study.
Conclusion: This project demonstrates that supervised machine learning techniques can effectively predict customer churn in the telecommunications industry. Among the evaluated models, Logistic Regression achieved the best predictive performance and can help organizations identify customers at risk of leaving and improve retention strategies.
