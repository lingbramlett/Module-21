# Module-21
Deep Learning Challenge
 Overview
This project utilizes a charity dataset to build a predictive model for Alphabet Soup, helping them identify applicants with the highest likelihood of success. The data was preprocessed using Pandas and Scikit-Learn, then used to train and evaluate a neural network model.

The workflow includes:
Data preprocessing in Google Colab
Data scaling using StandardScaler
Building a binary classification model with TensorFlow/Keras
Optimizing the model to improve accuracy

Data Preprocessing
Target Variable:

IS_SUCCESSFUL (indicates whether an organization was successful)
Feature Variables:

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
Variables Removed:

EIN, NAME (these are identifiers and do not contribute to model predictions)
Model Development
Neural Network Architecture:

Number of Layers: Tried multiple variations
Neurons: Experimented with different neuron counts
Activation Functions: Tested ReLU and other activations


