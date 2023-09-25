# RBF-Network-Optimization-and-Analysis
Certainly, here's a more polished and structured version of the project description:

---

## Overview

This repository contains the code and analysis for the implementation of a Radial Basis Function (RBF) network. The primary objective of this project is to construct an RBF network with a single input variable, one output variable, and a Gaussian basis function. The core methodology employed here leverages K-means clustering to determine optimal Gaussian centers for the RBF network.

## Input Data Generation

The input data for this project is generated through the sampling of a mathematical function:

\[h(x) = 0.5 + 0.4\cos(2.5\pi x)\]

To mimic real-world scenarios, noise is introduced to the data, sampled from a uniform distribution within the interval [-0.1, 0.1]. Additionally, the 'x' values are uniformly distributed in the range [0.0, 1.0].

## Observations and Analysis

As we increase the bases the error is supposed to reduce, this can be inferred from the graphs. Change in learning rate does not have much impact but with a learning rate of 0.02, we get better output. There is not a lot of improvement in the error rate after 10. We can see that the error rate is higher for different variances as compared to the same variance. At lower bases the same variance shows better performance while different variance has better at higher bases.

## Conclusion

For the lower number of bases the same variance performed better while for higher bases different variances have a better performance. There is not much of a difference between the two since we have only 100 epochs. The overall performance is better for the same variance with a learning rate of 0.02 and 15 bases.


