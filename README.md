# Credit_Risk_Analysis

## Overview of the Analysis

The purpose of this analysis is to predict credit risk using machine learning models. Machine learning models offer quicker and most reliable loan experience for customers. We are using techniques like resampling and boosting to make most of our data and the model we choose to implement.

## Results

### Use Resampling Models to Predict Credit Risk:

In this section we are evaluating four machine learning models by using resampling to determine which is better at predicting credit risk.

1. Oversampling data using RandomOverSampler:

The RandomOverSampling model has an accuracy of 65.2% and it predicts the high risk loans with precision of 0.01 and recall of 0.61.

2. Oversampling data using SMOTE:

The SMOTE model has an accuracy of 65.8% and it predicts the high risk loans with precision of 0.01 and recall of 0.72.

3. Undersampling data using  ClusterCentroids:

The ClusterCentroids model has an accuracy of 65.2% and it predicts the high risk loans with precision of 0.01 and recall of 0.69.

4. Combination of over and under sampling using SMOTEENN:

The SMOTEENN model has an accuracy of 55.4% and it predicts the high risk loans with precision of 0.01 and recall of 0.74.

### Ensemble Learners:

In this section, we will compare two ensemble algorithms to determine which algorithm results in the best performance. We will train a Balanced Random Forest Classifier and an Easy Ensemble AdaBoost classifier.

5. Balanced Random Forest Classifier:

The Random Forest model has an accuracy of 99.6% and it predicts the high risk loans with precision of 0.9 and recall of 0.36.

6. Easy Ensemble AdaBoost Classifier:

The Easy Ensemble AdaBoost model has an accuracy of 99.6% and it predicts the high risk loans with precision of 0.88 and recall of 0.38.

7. Easy Ensemble Classifier:

The Easy Ensemble Classifier model has an accuracy of 99.2% and it predicts the high risk loans with precision of 0.92 and recall of 1.0.


## Summary

To predict the credit risk, we are using different sampling and ensemble methods. Of all the methods ensemble methods are performing relatively well compared to the sampling.

Easy Ensemble Classifier is better at predicting the high risk credit loans with 99.6% accuracy and 100% recall. However, we must be careful with overfitting the model when recommending this model.


