# Stealing Machine Learning Models
## Understanding the difference between real and stolen models
Machine Learning as a Service (MLaaS) is a growing business, where more and more companies make their algorithms publicly accessible through Application Programming Interfaces (APIs). Creating such models can be expensive and time-consuming, which makes it attractive for adversaries to extract those models through querying the API with malicious data. This way, the adversary can create a surrogate model for own purposes. Recent research has shown, that it is possible to create a surrogate model that classifies input with 100% the same accuracy as the original model. Since some of these models cannot be distinguished in terms of classifications, output probabilities, or decision boundaries, the goal of this thesis is to identify where these models differ. For this purpose, we introduce a new approach, defined as the Model Tomography, where we visualize the internal behavior of the models.

## General info
This Repository includes the experimental setup for my master thesis.

## Model extraction attack
The used model extraction attacks are adapted from the work of Tramer et al. (2016). 

## Model Tomography
We introduce a new approach, to identify the differences between surrogate models and models trained on genuine data.

## Setup
We focus on the extraction of neural networks. The folder for the binary classifier includes datasets used for the experiment. 
To run the simulation, we make use of the Makefile located in the neural-nets directory.


