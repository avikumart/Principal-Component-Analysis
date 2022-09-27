# Principal-Component-Analysis
This notebook contains simple explanation of PCA and it's importance in data reduction to avoid multi-collinearity in given variables of data.

## Overview 

- Principal component analysis is a dimention reduction technique that finds the variance maximizing directions onto which to project the data.
- Linear dimensionality reduction using Singular Value Decomposition of the data to project it to a lower dimensional space. The input data is centered but not scaled for each feature before applying the SVD.
- Principal components are calculated to reduce variance of features and thus reducing dimentionality of variables in dataset.

![image](https://user-images.githubusercontent.com/88608935/192514171-f88d93b8-31a4-49b2-a4e2-d8e3f2476a31.png)

## Table of contents of this repo:

1) Library imports
2) Plotting continues numerical features
3) PCA Object
4) Plotting explained variance ratio
5) Plotting explained variance ratio
6) Plotting cummulative explained variance
