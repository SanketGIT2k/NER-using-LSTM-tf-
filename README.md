# NER-using-LSTM-tf-

The project contains data and python files that have data cleaning, data conversion and tensorflow model for doing NER operation on Legal Data from Indian Judiciary.

#Data

The data folder contains four files from which TEST.csv is the file that is cleaned and optimised to work better with the model. Cleaning is done by removing a percentage of stop words and reducing the exceptionally high data. This was done manually.

#Python Files

The NLP NER 2.ipynb file contains the preprocessing of the data from TEST.csv, model generation and model evaluation.

The fileDataToExel.ipynb file takes data in .txt files from a folder, seperating the sentences and then appending it into a excel file.

The NLP.ipynb files contain basic data processing that we did to understand the data better. No output from this file is used in the actual project. This was done to learn more about the data and try models on the data to understand the task that we are trying to do.
