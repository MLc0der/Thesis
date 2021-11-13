# Thesis
## Abstract

Main purpose of this diploma thesis is to investigate and study the applications of
Machine learning techniques and algorithms in problems of Financial Mathematics such
as derivative pricing and implied volatility estimation. Utilization of data, as well as
computational resources, aims to find more efficient and faster approaches compared to
classical numerical methods, which are traditionally used in the field of Computational
Finance.

## Introduction

Through this diploma thesis, we aim to develop Machine Learning algorithms that are able to compute the fair price of financial derivatives such as Options, learning from standard pricing models (Black-Scholes, Levy processes). In addition, by inversing this process, we also develop artificial neural networks (ANN), trained to estimate the implied volatility (IV) for an asset's price. 

We develop and compare different network architectures, such as Feedforward and radial basis function networks and different models, such as Black-Scholes and Normal inverse Gaussian (NIG) models.

## Data
To apply neural network regression techniques, it is necessary to provide
whatever model should be trained with sample data, in order to effectively
learn the relationship of input and output of the Black-Scholes function and
its inverse with regard to volatility.


## Architecture Investigation
In addition to the choice of model architecture, the selection of hyper-parameters
for the chosen model is of high interest with regard to its performance in training.
It is not at all trivial to see which combination of  activation function, optimizer 
and learning rate will yield better results. 
To that end, a grid search among potentially reasonable choices was conducted
on the reduced training data in order to and favorable model configurations.
