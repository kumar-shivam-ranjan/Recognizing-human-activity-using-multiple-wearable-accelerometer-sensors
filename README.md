# Recognizing human activity using multiple wearable accelerometer sensors
#### Human Activity Recognition, is the problem of predicting what kind of activity a person is performing based on a signals detected by smartphone sensors on their waist.
#### Two types of sensors present in smartphones are:
#### 1. `Accelerometer`
#### 2. `Gyroscope` 
#### Accelerometer measures acceleration and Gyroscope measures angular velocity.

## How the data was prepared?
1. 30 volunteers referred to as subjects  performed the experiment for data collection wearing smartphones sensors on their waist.
2. The two smartphone sensors captured the  **3 axial linear acceleration** as well as the  **3 axial angular velocity** of the subject.
3. The sensor signals were sampled in fixed-width sliding windows of **2.56 sec** and **50% overlap** (128 readings/window).
4. The data were recorded at the constant  frequency of **50Hz**  (50 data points  were recorded each second ) 

## Quick Overview of the Dataset
+ Data is downloaded from following source: 
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones
+ Feature names are present in UCI_HAR_dataset/features.txt
+ **Train Data**
  + `UCI_HAR_dataset/train/X_train.txt`
  + `UCI_HAR_dataset/train/subject_train.txt`
  + `UCI_HAR_dataset/train/y_train.txt`
+ **Test Data**
  + `UCI_HAR_dataset/test/X_test.txt`
  + `UCI_HAR_dataset/test/subject_test.txt`
  + `UCI_HAR_dataset/test/y_test.txt`
## Problem Statement 
### Predict one of the following six activities that a Smartphone user is performing at that 2.56 Seconds time window by using either 561 feature data or raw features of 128 reading.
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying
## LSTM architecture that will solve HAR problem
![Picture1](https://user-images.githubusercontent.com/42781233/95282887-fe915580-0877-11eb-8b3d-3ab3c55f1801.jpg)

