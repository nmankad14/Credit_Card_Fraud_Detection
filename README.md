# Credit_Card_Fraud_Detection

## **Overview**  
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Given the imbalance in real-world fraud data, various preprocessing, feature engineering, and modeling strategies are applied to improve fraud detection accuracy.  

## **Dataset**  
- The dataset is hypothetical and consists of credit card transactions with multiple features, including transaction amount, location, time, and customer details.  
- The dataset is highly imbalanced, with far fewer fraudulent transactions than legitimate ones.  

## **Objectives**  
- Identify fraudulent transactions using machine learning models.  
- Handle class imbalance through oversampling techniques like **SMOTE**.  
- Extract meaningful insights from transaction patterns.  
- Evaluate model performance using metrics like **AUC-ROC**, **Precision**, **Recall**, and **F1-score**.  

## **Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, Imbalanced-learn  
- **Machine Learning Models:** Random Forest, Logistic Regression, XGBoost, Decision Tree

## **Exploratory Data Analysis (EDA) & Visualizations**
To understand fraudulent transactions better, we performed various visualizations, leading to key insights:

- Fraudulent transactions are more frequent at night, with a peak around 22:00 (10 PM).
- Middle-aged individuals (30-60 years old) are more prone to fraudulent transactions, with a peak around 35-40 years old.
- Fraudulent transactions tend to occur within distances of 70-80 km from the user's usual transaction location.
- Transaction amounts show a skewed distribution, with most transactions involving small amounts, but high-value transactions are more likely to be fraudulent.
- Fraud is more common on weekends, possibly due to reduced monitoring.

These insights help in feature selection and improving the model’s ability to detect fraud.

## **Feature Engineering & Data Preprocessing**  
- Encoding categorical variables using **Label Encoding**.  
- Handling class imbalance with **SMOTE (Synthetic Minority Oversampling Technique)**.  
- Removing correlated features to avoid **multicollinearity**.  

## **Model Training & Evaluation**  
- Models used: **Random Forest, XGBoost, Decision Tree.**
- Performance evaluated using **AUC-ROC Curve, Precision, Recall, and Confusion Matrix**.  
- Feature importance analysis performed using **Gini Importance**.  

## **Results**  
- Achieved an **AUC-ROC score of 0.85**, indicating good fraud detection capability.  
- Random Forest and XGBoost performed well in identifying fraudulent transactions.  

## **Future Improvements**  
- **Hyperparameter tuning** to improve model performance.  
- Experimenting with **deep learning models** for better fraud detection.  
- Deploying the model as a **real-time fraud detection API**.
