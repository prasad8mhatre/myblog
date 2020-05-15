---
layout: post
title:  "Sampling algorithm - Oversampling"
date:   2020-05-14 21:03:36 +0530
categories: ML python sampling-algorithm
---
Sampling algorithm for ML is used when we have imbalanced dataset.
There are two type of sampling in imbalanced dataset - Oversampling and undersampling.AMDO: An Over-Sampling Technique for Multi-Class Imbalanced Problems


#### Problem Statement
Oversampling - 
Multi-class imbalanced problems have attracted growing attention from the real-world classification tasks in engineering. The underlying skewed distribution of multiple classes poses difficulties for learning algorithms, which becomes more challenging when considering overlapping between classes, lack of representative data, and mixed-type data. In this work, we address this problem in a data-oriented way. Motivated by a recently proposed over-sampling technique designed for numeric data sets, Mahalanobis Distance-based Over-sampling (MDO), we use this technique to capture the covariance structure of the minority class and to generate synthetic samples along the probability contours for learning algorithms. Based on MDO, we further improve the over-sampling strategy and generalize it for mixed-type data sets. The established technique, Adaptive Mahalanobis Distance-based Over-sampling (AMDO), introduces GSVD (Generalized Singular Value Decomposition) for mixed-type data, develops a partially balanced resampling scheme and optimizes the sample synthesis. Theoretical analysis is conducted to demonstrate the reasonability of AMDO. Extensive experimental testing is performed on 15 multi-class imbalanced benchmarks and two data sets for precipitation phase recognition in comparison with several state-of-the-art multi-class imbalanced learning methods. The results validate the effectiveness and robustness of our proposal.

#### Solution
IEEE paper implementation: 
[IEEE paper](https://ieeexplore.ieee.org/document/8065074)


#### Demo
[Implementation](https://github.com/prasad8mhatre/ML-Over-Sampling/blob/master/IDBMIOT-thyroid.ipynb)


#### Reference
[IEEE paper](https://ieeexplore.ieee.org/document/8065074)
[Implementation](https://github.com/prasad8mhatre/ML-Over-Sampling)
