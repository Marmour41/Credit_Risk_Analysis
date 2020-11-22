# Credit_Risk_Analysis

## Overview of the Analysis
The purpose of this analsyis was to assesss credit risk using machine learning models. In order to do this, I've analyzed the performance of each model using the precision, recall, and balanced accuracy scores.

## Results
- Naive Random Oversampling
    - For the [Naive Random Oversampling Model](Module-17-Challenge-Resources/images/naive_random_oversampling.png), the precision score for high-risk and low-risk accounts was 0.01 and 1, respectively. The recall scores were 0.66 and 0.64 for high-risk and low-risk. The balanced accuracy score was 0.64.
- SMOTE Oversampling
    - For the [SMOTE Oversampling Model](Module-17-Challenge-Resources/images/smote_oversampling.png), the precision scores were the same as the Random Oversamplmilng Model. The recall values were 0.61 for high-risk and 0.69 for low-risk. The balanced accuracy score was 0.65. 
- Undersampling
    - Using the [Undersamplming Method](Module-17-Challenge-Resources/images/undersampling.png), the precision score for high-risk and low-risk accounts was 0.01 and 1, respectively. The recall scores were 0.67 for high-risk and 0.42 for low-risk. The balanced accuracy score was 0.54.
- Combination (Over and Under) Sampling - SMOTEENN
    - For the [SMOTEENN Method](Module-17-Challenge-Resources/images/smoteenn.png), the precision values were once again 0.01 and 1. The recall values were 0.72 for high-risk and 0.57 for low-risk. The balanced accuracy score was 0.64. This algorithm has similar results to the over and undersampling methods.  
- Ensemble Classifiers
    - For the [Balanced Random Forest Classifier](Module-17-Challenge-Resources/imgaes/balanced_random_forest.png), the precision score for high-risk is 0.03, and 1 for low-risk. The recall scores were 0.70 for high-risk and 0.87 for low-risk. The balanced accuracy score was 0.79. 

    - For the [Easy Ensemble Classifier](Module-17-Challenge-Resources/images/easy_ensemble.png), the precision score for high-risk and low-risk were 0.09 and 1, respectively. The recall scores were 0.92 for high-risk and 0.94 for low-risk. The balanced accuracy score was 0.93.

## Summary
Based on the performance of each of these models, the Easy Ensemble Classifier had the best results for predicting credit risk for each account due to its high recall scores and high accuracy scores. I'd recommend using this model to predict credit risk.  