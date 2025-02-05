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

## **Exploratory Data Analysis (EDA)**  
Key findings from data visualization:  
- Fraudulent transactions are more frequent at **night**.  
- More fraud cases occur around the **22nd hour**.  
- Middle-aged individuals experience a higher number of fraudulent transactions.  
- Higher fraudulent transactions occur within **70-80 km distance**.  
- Transaction amounts show a **skewed distribution**, with a few high-value transactions being fraudulent.  

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
