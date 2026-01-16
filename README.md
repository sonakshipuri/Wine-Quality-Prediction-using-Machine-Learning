# Wine Quality Prediction using Machine Learning

End-to-end machine learning project for predicting wine quality using physicochemical features, with model comparison, hyperparameter tuning, and evaluation using F1-score and ROC-AUC.

## Overview
This project implements an end-to-end machine learning pipeline to classify wine quality as high or low using physicochemical attributes of red wine samples. The focus is on building, comparing, and evaluating multiple classification models while addressing class imbalance and model interpretability.

## Workflow
- Exploratory Data Analysis (EDA) to study feature distributions and correlations  
- Binary target formulation for practical quality classification  
- Data preprocessing with stratified train-test split and feature scaling  
- Model training using Logistic Regression, Decision Tree, Random Forest, and XGBoost  
- Hyperparameter tuning with GridSearchCV  
- Model evaluation using F1-score, ROC-AUC, and confusion matrices  
- Feature importance analysis to interpret model predictions  

## Models and Evaluation
Model performance is assessed using accuracy, precision, recall, F1-score, and ROC-AUC.  
F1-score is prioritized due to class imbalance, and ensemble models (Random Forest and XGBoost) achieve the strongest overall performance after tuning.

## Key Insights
- Ensemble models outperform baseline classifiers in distinguishing high-quality wines  
- Alcohol content emerges as the most influential feature affecting wine quality  
- ROC-AUC analysis confirms robust classification capability of tuned models  

## Tools and Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

## Conclusion
This project demonstrates a complete machine learning workflow, combining data analysis, model optimization, rigorous evaluation, and interpretability to produce reliable wine quality predictions.
