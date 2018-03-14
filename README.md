# Activity-Recognition-System-Analysis


In this problem, I attempt to classify the activities of humans based on time series data obtained by a Wireless Sensor Network. The dataset was taken from the UCI repository, which can be accessed at the following link https://archive.ics.uci.edu/ml/datasets/Activity+Recognition+system+based+on+Multisensor+data+fusion+(AReM)

# Dataset Description

The dataset contains 7 folders that represent seven types of activities. In each folder, there are multiple files each of which represents an instant of a human performing an activity. Each file contains 6 time series collected from activities of the same person. There are 88 instances in the dataset, each of which contains 6 time series and each time series has 480 consecutive values. For this classification task, datasets 1 and 2 in folders bending1 and bending2, as well as datasets 1, 2, 3 in other folders are kept as testing data while the other datasets will be used as training data to train the classification model. 

# Analysis

The classification of the given time series dataset along with analysis can be seen in the jupyter notebook file name AReM_Notebook.ipynb.
