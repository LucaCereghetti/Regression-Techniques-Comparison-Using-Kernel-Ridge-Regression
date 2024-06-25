# Regression Techniques Comparison Using Kernel Ridge Regression
## Overview
This repository contains materials and code for exploring various regression techniques, with a focus on Kernel Ridge Regression (KRR) using different kernel functions. Kernel Ridge Regression is particularly advantageous for capturing complex relationships within data by mapping input features into high-dimensional spaces through the use of kernel functions.

## Kernel Functions
The [kernel_functions_def.ipynb](./kernel_functions_def.ipynb) notebook is dedicated to defining and implementing a variety of kernel functions. Specifically, it addresses the use of Radial Basis Function (RBF), Matern, and Laplacian kernels, and investigates the potential of combining these kernels to enhance regression performance:

- RBF Kernel: Effective in capturing local patterns and sensitive to the distance between data points.
- Matern Kernel: Offers flexibility with an additional parameter that controls smoothness.
- Laplacian Kernel: Emphasizes differences between data points more sharply than the RBF kernel.

These functions are used to compute kernel matrices $𝐾$ for training data and $𝐺$ for test data, forming the foundational basis for implementing kernel ridge regression. This methodology provides robust and flexible tools for regression tasks, enhancing the model training process.

## Regression Models and Error Analysis
The [RKHS_def.ipynb](./RKHS_def.ipynb) notebook delves into the computation and comparison of different regression models, focusing on error analysis. The outputs of the codes include various error metrics, facilitating a comprehensive comparison of the models' performances. For this analysis, a real estate dataset is utilized, which includes features such as:

- Transaction date
- House age
- Distance to the nearest MRT station
- Number of convenience stores
- Latitude
- Longitude
- House price per unit area

## Objectives
By comparing different regression techniques—linear regression, ridge regression, KRR, and KRR with various kernel combinations—using multiple error metrics, this project aims to determine the most effective approach for the given dataset. This thorough comparison provides valuable insights into the strengths and limitations of each method in predicting house prices.

## Conclusion
This repository offers a comprehensive exploration of kernel ridge regression and its applications in real estate valuation. The materials and code provided can serve as a valuable resource for understanding and implementing advanced regression techniques.


