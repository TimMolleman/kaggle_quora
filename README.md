# Kaggle_Quora

This repository contains two Python files that were created to find a solution for the 'Quora Question Pairs' problem on Kaggle. 
To run the XGBoost model as well as the LSTM model code, one should have the right data files in the right folder. This folder should be called 'Data' and should contain the following files:

* train_data.csv: Contains the in-class training dataset (used for XGBoost)
* train_labels.csv: Contains the labels for the in-class training dataset
* train_official.csv: Contains the larger training set of the original competition (used for LSTM)
* test_data.csv: Contains the test dataset
* GoogleNews-vectors-negative300.bin: Contains Google pre-trained word vectors

If the data is in the right place, the code will run smoothly!