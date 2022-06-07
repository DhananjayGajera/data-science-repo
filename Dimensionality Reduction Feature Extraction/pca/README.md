## Principal component Analysis(PCA)
> Principal components this way, will allow you to reduce dimensionality without losing much information, and this by discarding the components with low information and considering the remaining components as your new variables.

1. Subtract the mean and dividing by the standard deviation for each value of each variable.

2. After standardization all the variables will be transformed to the same scale.

3. Then apply coveriance matrix computation because to see if there is any relationship between them or not.

4. Eigenvectors and eigenvalues are the linear algebra concepts that we need to compute from the covariance matrix in order to determine the principal components of the data.

5. now choose whether to keep all these components or discard those of lesser significance (of low eigenvalues), and form with the remaining ones a matrix of vectors.

6. In last multiplying the transpose of the original data set by the transpose of the feature vector.
