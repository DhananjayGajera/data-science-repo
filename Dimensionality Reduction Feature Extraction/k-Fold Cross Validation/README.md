# k-Fold Cross Validation

What is k-Fold Cross Validation?
>  k-Fold introduces a new way of splitting the dataset which helps to overcome the test only once bottleneck.

How k-Fold work?
1. Choose number of folds value means **K** value. usually we are select 5 or 10.basically value is less then dataset length.
2. Now splite dataset in equal part like number of folds same as k value time.
3. Then k – 1 folds as the training set and remaining fold will be the test set.
4. Train the model on the training set. 
5. Validate on the test set
6. Save the result of the validation
7. we have to repeat step same as k value times.
