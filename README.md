# Credit_Risk_Analysis
Machine Learning

## Analysis and Purpose
This project has been undertaken on behalf of "Fast Lending", a fictitious peer to peer lending services company that uses machine learning to predict credit risk. Credit Risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques have been employed to train and evaluate models with unbalanced classes. This analysis includes evaluating several models to understand their efficiency to predict credit risk. The models used for this analysis include - 

- Sampling models to predict credit risk - **RandomOverSampler , Synthetic Minority Oversampling Technique (SMOTE) Oversampling, Cluster Centroid Undersampling**
- **SMOTEENN** algorithm to predict credit risk
- Ensemble Classifiers to predict credit risk - **BalancedRandomForestClassifier, EasyEnsembleClassifier**

## Resources
- Data : LoanStats_2019Q1.csv
- Software : Python, Jupyter Notebook

## Results

#### Random Oversampling Model

![](images/accuracy_score_random_oversampling.png)

![](images/random_oversampling_confusion_matrix.png)

![](images/random_oversampling_classification_report.png)


