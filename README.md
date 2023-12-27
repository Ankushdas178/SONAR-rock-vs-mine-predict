# SONAR Rock vs Mine Prediction


## Background

SONAR (Sound Navigation Ranging) is a technology that uses sound waves to detect and locate objects underwater. In this project, we aim to predict whether the object detected by SONAR is a rock or a mine based on the analysis of SONAR signals. SONAR technique has exploited the discovery of rocks and minerals which would have been very difficult otherwise. The technique exploits certain parameters which will aid to detect the surface targets or obstacle such as a rock or a mine.

## Dataset

The dataset has been collected from UCI Repository. It has come across 61 features which define and differentiate Rocks and Mines and comprises of 209 samples. This data is used for training and testing purpose. The Last column in this dataset indicates that, whether it's a mine or a rock, which is useful in prediction. The dataset is included in this repository.

## Model

The model used here is Logistic Regression. Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. Logistic Regression uses a sigmoid or logit function which will squash the best fit straight line that will map any values including the exceeding values from 0 to 1 range. So it forms an “S” shaped curve. Sigmoid func. removes the effect of outlier and makes the output between 0 to 1. As it a binary classification model it is perfect to predict if an object is mine or rock based on the sonar data.
