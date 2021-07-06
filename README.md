# Credit Risk Analysis

## Overview of the Analysis

The purpose of this analysis was to create supervised machine learning models to predict credit risk. Basic logistic regression models were combined with oversampling and undersampling methods as well as two other models, the balanced random forest model and easy ensemble classifier model.

## Results

- Naive Random Oversampling:
![Results](images/img1.png)

- SMOTE Oversampling:
![Results](images/img2.png)

- Undersampling:
![Results](images/img3.png)

- SMOTEENN Sampling:
![Results](images/img4.png)

- Balanced Random Forest Classifier:
![Results](images/img5.png)

- Easy Ensemble AdaBoost Classifier:
![Results](images/img6.png)

## Summary

The results show that the oversampling and SMOTEENN sampling both result in similar accuracies with around 62-63% overall. The undersampling does worse at around 50%, while the two ensemble classifiers do well with over 90% accuracy.

Overall, I would choose either the random forests model or the AdaBoost model based on the high accuracy and precision/recall.
