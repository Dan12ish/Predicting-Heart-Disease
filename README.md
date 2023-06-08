# Predicting-Heart-Disease
Machine Learning Project: Predicting Heart Disease using KNN

## 1) Steps:  
. Importing the dataset.  
. Data exploration.  
. Scalar transformation.  
. Finding the optimal value of K.  
. Predicting the heart disease using KNN.  

## 2) Conclusion:  

1. Confusion Matrix
Each row: actual class
Each column: predicted class

First row: No Heart Disease, the negative class:
. 27 were correctly classified as No heart disease . True negatives.
. Remaining 11 were wrongly classified as heart disease. False positive.

Second row: Heart Disease, the positive class:
. 8 were incorrectly classified as No heart disease. False negatives.
. 45 were correctly classified as heart disease. True positives.

2. Precision
Precision measures the accuracy of positive predictions. Also called the precision of the classifier ==> 79 %

3. Recall
Precision is typically used with recall (Sensitivity or True Positive Rate). The ratio of positive instances that are correctly detected by the classifier ==> 79 %

4. F1
F1 score is the harmonic mean of precision and recall. Regular mean gives equal weight to all values. Harmonic mean gives more weight to low values ==> 79 %
