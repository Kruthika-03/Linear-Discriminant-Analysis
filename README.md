# Linear-Discriminant-Analysis
Linear Discriminant Analysis to perform dimensionality reduction

## Algorithm
1. First, we need to compute scatter matrices for inter class and intra class
2. Next, we need to compute the eigen vectors and its corresponding eigen values for the given scatter matrices
3. Sorting of eigen values and selection of the top k
4. A new matrix is created where in the eigenvectors are mapped to the k eigenvalues
5. The new feature is obtained taking the dot product of the data and the matrix

## Dataset Description
I have considered the Wine Data Set from the UCI Machine Learning Repository. Here the wine is to be classified into three classes based on the chemical analysis which determines the origin of wines. The Data is multivariate, integer and real.

![dataset](https://user-images.githubusercontent.com/58825386/122722309-2b16c180-d28f-11eb-81aa-3b7715c1f4ab.png)

