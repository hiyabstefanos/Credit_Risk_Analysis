# Credit_Risk_Analysis

Use imbalanced-learn and scikit-learn to create a supervised machine learning model.

## Overview of the analysis:

In this analysis we will be using supervised machine learning to predict credit risk. This allows for a more reliable loan experience with more accurate targeting.

## Results: 

### Naive Random Oversampling

<img width="957" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/89358080/150650876-72153174-aa2d-4d24-99a1-372db9700327.png">

- accuracy scores: 64%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 59%
    - low risk
        - precision:100%
        - recall: 69%
        

### SMOTE Oversampling

<img width="943" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/89358080/150650887-7637324e-cf3a-4ee8-b379-e489d0156f14.png">

- accuracy scores: 62.1%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 59%
    - low risk
        - precision: 100%
        - recall: 66%
        
### Cluster Centroid Undersampling

<img width="945" alt="Cluster Centroid Undersampling" src="https://user-images.githubusercontent.com/89358080/150650896-4aa76e65-7f7b-4da2-bda5-ca664a6db09a.png">

- accuracy scores: 52.9%%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 61%
    - low risk
        - precision: 100%
        - recall: 45%

### SMOTEENN

<img width="935" alt="SMOTEENN" src="https://user-images.githubusercontent.com/89358080/150650907-845bd6b4-8ced-4668-af38-2fcca0b7fb93.png">

- accuracy scores: 61.1%
- recall scores:
    - high risk
        - precision: 1%
        - recall: 68%
    - low risk
        - precision: 100%
        - recall: 54%

### Balanced Random Forest Classifier

<img width="944" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/89358080/150650908-2dd1388a-9d09-43ea-a128-ce5b47920c63.png">

- accuracy scores: 78.8%
- recall scores:
    - high risk
        - precision: 3%
        - recall: 68%
    - low risk
        - precision: 100%
        - recall: 90%

### Easy Ensemble Classifying

<img width="1015" alt="Easy Ensemble Classifying" src="https://user-images.githubusercontent.com/89358080/150650915-5ae5e580-ef9a-41ac-b7bb-3fc77478d2f9.png">

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
