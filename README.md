# Credit_Risk_Analysis

Use Python and Scikit-learn to create a supervised machine learning model.

## Overview of the analysis:

In this analysis we will be using supervised machine learning to predict credit risk. This allows for a more reliable loan experience with more accurate targeting.

## Results: 

### Naive Random Oversampling
- accuracy scores: 64%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 59%
    - low risk
        - precision:100%
        - recall: 69%

### SMOTE Oversampling
- accuracy scores: 62.1%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 59%
    - low risk
        - precision: 100%
        - recall: 66%
        
### Cluster Centroid Undersampling
- accuracy scores: 52.9%%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 61%
    - low risk
        - precision: 100%
        - recall: 45%

### SMOTEENN
- accuracy scores: 61.1%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 68%
    - low risk
        - precision: 100%
        - recall: 54%

### Balanced Random Forest Classifier
- accuracy scores: 78.8%
- recall scores:
    - high risk
        - precision: 3%
        - recall: 68%
    - low risk
        - precision: 100%
        - recall: 90%

### Easy Ensemble Classifying
- accuracy scores: 93%
- recall scores:
    - high risk
        - precision: 6%
        - recall: 92%
    - low risk
        - precision: 100%
        - recall: 94%




## Summary: 

Using these 6 models to optimize credit risk, we find the best model to use is Easy Ensemble Classifying due to the highest accuracy of 93%, a high risk recall rate of 92%, and a low risk recall of 94%.