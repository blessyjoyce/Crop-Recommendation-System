# Crop Recommendation System

## Overview

The Crop Recommendation System is a Machine Learning and Deep Learning-based application that recommends the most suitable crop for cultivation based on soil nutrients and environmental conditions. The system assists farmers and agricultural professionals in making data-driven decisions to improve crop productivity and optimize resource utilization.

## Problem Statement

Selecting the right crop is a critical factor in achieving higher agricultural yield. This project analyzes soil and weather parameters and recommends the most suitable crop for cultivation using a trained neural network model.

## Dataset Features

The model uses the following input parameters:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Value
- Rainfall

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Joblib

## Project Workflow

### 1. Data Collection
- Agricultural dataset collected from Kaggle.
- Dataset contains soil nutrient values, weather conditions, and crop labels.

### 2. Data Preprocessing
- Feature selection performed on input parameters.
- Min-Max Scaling applied to normalize data.
- Crop labels encoded using One-Hot Encoding.
- Dataset split into training and testing sets.

### 3. Exploratory Data Analysis (EDA)
- Correlation Heatmap
- Feature Pair Plot Analysis
- Crop Distribution Visualization
- Feature Distribution Boxplots

### 4. Model Development
A Deep Neural Network (DNN) was developed using TensorFlow/Keras with:

- Input Layer (7 Features)
- Dense Layer (128 Neurons, ReLU)
- Dense Layer (64 Neurons, ReLU)
- Dense Layer (32 Neurons, ReLU)
- Output Layer (22 Crop Classes, Softmax)

### 5. Model Training
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 25
- Batch Size: 32

### 6. Model Evaluation
The trained model was evaluated using:

- Accuracy Score
- Loss Analysis
- Classification Report
- Training and Validation Curves

### 7. Model Deployment
The trained model and scaler were saved for deployment:

- crop_recommendation_model.keras
- crop_recommendation_model.h5
- crop_recommendation_scaler.joblib

## Features

- Predicts suitable crops based on soil and environmental parameters.
- Data preprocessing and normalization.
- Deep Learning-based crop classification.
- Visualization and exploratory data analysis.
- Model saving for future deployment.

## Expected Outcome

The system recommends the most appropriate crop based on the provided agricultural conditions, helping farmers improve productivity and make informed cultivation decisions.

## Future Enhancements

- Real-time weather integration.
- Web and mobile application deployment.
- Recommendation of fertilizers and irrigation requirements.
- Continuous model retraining with updated agricultural datasets.

## Author

**Mangam Blessy**

Computer Science Graduate | Machine Learning Enthusiast | Aspiring Software Developer
