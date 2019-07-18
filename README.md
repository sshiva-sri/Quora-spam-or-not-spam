# Quora-spam-or-not-spam
-----------------------------

• Problem statement:
------------------

Predicting given a Quora question is genuine or spam. 

•Problems Faced:
---------------
Main problem faced was 4GB RAM was not sufficient, system got stuck once started with the training the model.

So tried processing in Kaggle Kernel( https://www.kaggle.com/) . Training the model utilized 10GB of RAM

•	Solution:
------------

Data that was available for modelling included question ID, question description and target (spam or not) . The features from question description were extracted using Glove Embedding as part of processing data. 

•	Experiments : 
----------------

Built models using CNN and LSTM. Using F1 score as the metric CNN gave better metrics compared to LSTM model.
