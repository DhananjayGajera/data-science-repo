# Handle Imbalanced Data

What is imbalanced data?
> Imbalanced data reflects an unequal distribution of classes within a dataset.

issue with imbalanced data
> Basically due to imbalanced data system can't able accurately predicting for both majority and minority class.

How to resolve imbalanced dataset
1. Choose Proper Evaluation Metric
2. Resampling
3. SMOTE
4. SMOTETomek
5. BalancedBaggingClassifier
6. Threshold moving

## 1. Choose Proper Evaluation Metric

* All knows accuracy of a classifier is the total number of correct predictions by the classifier divided by the total number of predictions.

* This is for well-balanced class but for inbalance dataset this not work.

* for a inbalance dataset F1 score is appropriate matric.

What is f1 score?
* F1 score is harmonic mean of the precision and recall.
> Here f1 score will reaches its best value at 1 and worst score at 0.

Formula:

>F1 = 2 (precision * recall) / (precision + recall)

> Precision: TP/(TP + FP)

> Recall: TP/(TP + FN)


## 2. Resampling
When we are using an imbalanced dataset at that time Resampling is used to upsample or downsample the minority or majority class.

 
* Undersampling:
> we can randomly delete rows from the majority class to match them with the minority class which is called undersampling.

* Oversampling:
>  we can oversample the minority class using replacement. 

## 3. Oversampling(SMOTE)
* SMOTE is technique to oversample the minority class. Simply adding duplicate records of minority class often don’t add any new information to the model

## 4.Oversampling(SMOTETomek)
SMOTETomek is a hybrid method
which uses an under sampling method (Tomek) in with an over sampling method (SMOTE).
