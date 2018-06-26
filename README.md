# ml-basics
jupyter notebooks for revising machine learning basics

## What is this?
I prepared these notebooks while preparing for interviews for research positions at tech companies. The goal was for me to revise (and implement) basic machine learning algorithms that I had studied several years ago. Many people have found them useful for their own learning, so I've made them public. 

This work is not yet polished - pull requests with improvements or extensions are welcome!

## Contents:

### k-means, GMMs and Gaussians.ipynb

* Multi-variate Gaussians
* K-means (clustering algorithm)
* Principal component analysis (dimensionality reduction)
* Gaussian Mixture Models and the Expectation-Maximisaion EM algorithm

![](https://raw.githubusercontent.com/paruby/ml-basics/master/pic/k-means.png)

### Linear Regression, K-fold Cross Validation, Gaussian Process Regression and Logistic Regression.ipynb

* Least squares linear regression
* Polynomial regression
* Cross validation
* Kernel ridge regression
* Gaussian process regression (a.k.a. 'kriging' in some circles)
* Logistic regression <- trivial case of neural network classification
* Multiclass logistic regression <- trivial case of neural network classification
* Backpropogation (an essential part of how neural networks are trained)

![](https://raw.githubusercontent.com/paruby/ml-basics/master/pic/gp-regression.png)

### Statistical Hypothesis Testing

(Note: this is a recap of statistical hypothesis testing *using kernels*, and ignores almost the entirety of the statistical hypothesis testing literature.)

* Maximum Mean Discrepency (MMD): do X and Y have the same distribution?
* Hilbert-Schmidt Independence Criterion (HSIC): are X and Y independent?

![](https://raw.githubusercontent.com/paruby/ml-basics/master/pic/hypothesis-testing.png)
