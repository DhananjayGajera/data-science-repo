# Backward Elimination

Backward Elimination:In backward elimination, we start with all the features and removes the least significant feature at each iteration which improves the performance of the model. We repeat this until no improvement is observed on removal of features.

How backward elimination work?

1. Select a P-value level(P-value = 0.05)
2. Fit the model with all features
3. find which feature has highest P-value?
4. remove highest P-value
5. repeat all step untill p-value of all features is more than significance level.

Well,Backward Elimination basically use when we have small dataset.

it will take time when we have large amount of feature, So we can use backward elimination for small or mid size dataset.
