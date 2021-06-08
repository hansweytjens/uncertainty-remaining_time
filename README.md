## README 
This repository contains the code for the paper "Learning Uncertainty with Artificial Neural Networks for Improved Remaining Time Prediction of Business Processes". There are five notebooks.

"CNN" is the convolutional neural network we used in our experiments.

"LSTM" is the long short-term memory network we used in our experiments

Both "CNN" and "LSTM" rely on the class ConcreteDropout in the "Concrete" notebook.

The "Learning" notebook provides a simplified training mechanism to train the CNN and LSTM models.

The loss functions used in "Learning" can be found in "Loss_functions".


## PyTorch
Our neural networks are built with PyTorch. Information and installation instructions can be found on https://pytorch.org/.


## Paper abstract
Artificial neural networks will always make a prediction, even when completely uncertain and regardless of the consequences. This obliviousness of uncertainty is a major obstacle towards their adoption in practice. Techniques exist, however, to estimate the two major types of uncertainty: model uncertainty and observation noise in the data. Bayesian neural networks are theoretically well-founded models that can learn the model uncertainty of their predictions. Minor modifications to these models and their loss functions allow learning the observation noise for individual samples as well. This paper is the first to apply these techniques to predictive process monitoring. We found that they contribute towards more accurate predictions and work quickly. However, their main benefit resides with the uncertainty estimates themselves that allow the separation of higher-quality from lower-quality predictions and the building of confidence intervals. This leads to many interesting applications, enables an earlier adoption of prediction systems with smaller datasets and fosters a better cooperation with humans. 
