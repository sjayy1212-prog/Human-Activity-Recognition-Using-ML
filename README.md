Human Activity Recognition Using Smartphone Sensor Data
Project Overview

This project focuses on Human Activity Recognition (HAR) using data collected from smartphone sensors. The objective is to classify human physical activities based on accelerometer and gyroscope signals captured from a waist-mounted smartphone.

The dataset contains recordings from 30 participants performing daily activities while carrying a smartphone. Machine learning models are trained to recognize and classify these activities based on extracted time-domain and frequency-domain features.

Activities Classified

The model predicts one of the following six activities:

Walking

Walking Upstairs

Walking Downstairs

Sitting

Standing

Laying

Dataset

The dataset was collected from 30 volunteers aged 19–48 years using a Samsung Galaxy S II smartphone equipped with:

3-axis accelerometer

3-axis gyroscope

Sensor data was recorded at 50 Hz and processed using sliding windows of 2.56 seconds (128 readings) with 50% overlap.

Preprocessing Steps

Noise filtering using signal processing techniques

Separation of body acceleration and gravitational acceleration

Feature extraction from time-domain and frequency-domain signals

Creation of feature vectors for each observation window

Project Workflow
1. Data Loading

Importing dataset and preparing it for analysis

2. Data Preprocessing

Handling missing values

Removing duplicate records

Checking class balance

3. Exploratory Data Analysis (EDA)

Feature distribution analysis

Visualization of sensor features

Dimensionality reduction using t-SNE

4. Model Training

Multiple machine learning models were implemented and compared:

Logistic Regression

Linear Support Vector Machine (SVM)

Kernel SVM

Decision Tree

Random Forest

5. Model Evaluation

Models were evaluated using:

Cross-validation

Hyperparameter tuning

Classification performance metrics

Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

t-SNE (Dimensionality Reduction)

Key Features

End-to-end machine learning pipeline

Feature engineering on sensor signals

Visualization of high-dimensional activity data

Comparison of multiple classification algorithms

Applications

Human Activity Recognition has applications in:

Healthcare monitoring

Fitness tracking

Smart homes

Elderly fall detection

Wearable technology
