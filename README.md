# Credit Risk Analysis

## Project Overview
The goal of this project was to test the performance of a variety of machine learning models on a credit
card dataset from LendingClub. Specifically, to test the predictive power of each model in determining the
credit risk of individuals in the dataset.
The models need to classify individuals as 'high risk' or 'low risk' from a credit perspective.
The dataset can be considered highly unbalanced, as the 'high risk' classification represents 347 of 68,817
individuals, or roughly 0.5% of the total.

## Results

### Balanced Accuracy Scores
| Model | Score    |
|-------|----------|
| Naive Random Oversampling | 0.832547 |
| SMOTE Oversampling | 0.844094 |
| Cluster Centroids | 0.820388 |
| SMOTE-ENN | 0.838890 |
| Balanced Random Forest Classifier | 0.783713 |
| Easy Ensemble AdaBoost Classifier | 0.931602 |

### Precision and Recall Scores

| Model | Score                          |
|---|--------------------------------|
| Naive Random Oversampling | ![NRO](Images/pre-rec-naive.png) |
| SMOTE Oversampling | ![NRO](Images/pre-rec-smote.png) |
| Cluster Centroids | ![NRO](Images/pre-rec-clusterCentroids.png) |
| SMOTE-ENN | ![NRO](Images/pre-rec-smoteenn.png) |
| Balanced Random Forest Classifier | ![NRO](Images/pre-rec-brfc.png) |
| Easy Ensemble AdaBoost Classifier | ![NRO](Images/pre-rec-eec.png) |

### Summary and Recommendations