# traffic_conjection_prediction
An ANN Project
Traffic Congestion Prediction using Artificial Neural Networks (ANN)
This repository contains an Artificial Neural Network (ANN) binary classification model developed to predict urban traffic congestion based on meteorological, temporal, and historical lag features. The model evaluates whether the traffic volume on a critical interstate highway will exceed a defined threshold of 2000 vehicles.  

📌 Project Overview
Urban traffic congestion leads to substantial economic loss, environmental pollution, and reduced quality of life. This project leverages an Intelligent Transportation Systems (ITS) framework using a Deep Learning approach (Feed-Forward Multilayer Perceptron) to proactively forecast traffic jams. 
Dataset: Metro Interstate Traffic Volume Dataset (I-94 Interstate highway, USA).  
Time Period: 2012 to 2017.  

🛠️ Tech Stack & Model ArchitectureLanguage: 
Python  Libraries: TensorFlow Keras, Pandas, NumPy, Scikit-learn, Joblib, Matplotlib  

ANN Architecture:
Input Layer (Scaled features)  
Hidden Layer 1: 128 Neurons (ReLU activation)  
Hidden Layer 2: 64 Neurons (ReLU activation)  
Hidden Layer 3: 32 Neurons (ReLU activation)  
Output Layer: 1 Neuron (Sigmoid activation for binary classification)  

Optimizer: Adam (LR = 0.001)  
Loss Function: Binary Crossentropy  

📊 Performance Metrics
The model demonstrated high proficiency across key evaluation metrics on the test dataset:  
Accuracy: 95.75%  
Precision: 96.51%  
Recall: 97.25%  
F1-Score: 96.87%  

🚀 How to Run the Inference Script
Clone this repository.
Ensure you have the required artifacts saved: traffic_classification_model.keras and scalers_and_features_classification.pkl.  
Run the interactive user input prediction script:Bashpython TrafficModel.py
Enter the requested temporal, environmental, and historical lag features to check if a traffic jam is expected.  
