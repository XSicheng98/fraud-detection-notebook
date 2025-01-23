**Credit Card Fraud Detection Using Machine Learning**
======================================================

**Project Overview**
--------------------

This project focuses on building a robust machine learning model to detect fraudulent credit card transactions. Fraud detection is a critical task in the financial sector, and this project demonstrates a complete pipeline for solving this problem, from data analysis and preprocessing to model deployment as a REST API.

**Key Features**
----------------

*   **End-to-End Machine Learning Pipeline**:
    
    *   Data preprocessing, feature engineering, and model training.
        
    *   Addressing class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
        
*   **Model**:
    
    *   Random Forest Classifier tuned for optimal performance.
        
    *   Achieved a **ROC AUC score of 99%**, highlighting the model's ability to distinguish between fraudulent and legitimate transactions.
        
*   **API Deployment**:
    
    *   Deployed the model using Flask as a REST API.
        
    *   Provides real-time predictions through the /predict endpoint.
        
*   **User-Friendly Documentation**:
    
    *   Clear explanations of each step and results.
        

**Project Workflow**
--------------------

1.  **Data Analysis**:
    
    *   Conducted Exploratory Data Analysis (EDA) to understand patterns and trends in fraudulent vs. non-fraudulent transactions.
        
    *   Visualized feature importance to understand key drivers of fraud.
        
2.  **Preprocessing**:
    
    *   Cleaned and prepared the dataset for modeling.
        
    *   Addressed class imbalance using SMOTE.
        
3.  **Model Development**:
    
    *   Trained a Random Forest model and tuned hyperparameters using RandomizedSearchCV.
        
    *   Evaluated the model using metrics such as precision, recall, F1-score, and ROC AUC.
        
4.  **API Deployment**:
    
    *   Developed a Flask REST API to provide predictions in real-time.
        
    *   Tested the /predict endpoint with sample data.
        
5.  **Documentation**:
    
    *   Documented the entire pipeline, including key findings and future improvements.
