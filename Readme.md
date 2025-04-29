# Breast Cancer Survival Prediction

## Authors
- Piero D'Aniello
- Diego Andrade
- Daniel Jiménez

## Project title
Breast Cancer Survival 

## Description
This project uses machine learning algorithms to predict breast cancer patient survival.The useddataset includes socio-demographic and medical information from 4024 patients. First, we preprocess the dataand splitted in three partitions. Then,we used balancing techniques beacuse our datset was unbalanced. FInally, we evaluated and selected the model

## File's outline
1. EDA
    
    i.General description
    
    ii.Handling outliers, null values
        
        a.Null values
        
        b.Outlier values
        
        c.Variables distribution
        
        d.Correlation
    
    iii.Normalization of numerical variables

2. Dataset partition

3. Evaluation balance techniques
    
    i.SMOTEEN
    
    ii.K-Means SMOTE
    
    iii.Wilcoxon test to prove best technique

4. Machine learning algorithms
    
    i.Apply K-Means Smote
    
    ii. AdaBoost
    
    iii.Random Forest
    
    iv.XGBoost
    
    v. Logistic regression

5. Model evaluation
    
    i. Metrics Table
    
    ii.ROC Curve
    
    iii. Confusion matrix

6. References


## Files
- `Project.ipynb`: Contains all code (data loading, preprocessing, model training, evaluation).
- `README.md`: Project description.
- `dataset.csv`: Input dataset used (if uploaded).

