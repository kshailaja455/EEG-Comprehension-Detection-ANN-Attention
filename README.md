

# EEG-Based Comprehension Detection in Online Learning Using Attention-Enhanced Neural Networks

#  Overview
This project focuses on detecting student understanding in online learning environments using EEG (Electroencephalogram) signals. The system analyzes brainwave activity and classifies whether a student has understood the lecture content.

#  Objective
To build an intelligent system that can:
1. Analyze EEG signals from students
2. Identify comprehension levels (Understood / Not Understood)
3.Enable real-time adaptive learning systems

#  Dataset Details
 1.14-channel EEG signal data
 2.Brainwave components:
    i. Alpha
    ii.Beta
    iii. Gamma
    iv. Theta
 3. Total Features: 86 per record
 4. Target: Binary classification (1 = Understood, 0 = Not Understood)

#  Methodology

# Data Preprocessing
1. Missing value handling (mean imputation)
2. Normalization using MinMaxScaler
3. Train-Test Split (80:20)
4. Class imbalance handled using SMOTE

# Feature Engineering
1. PCA (Principal Component Analysis) for dimensionality reduction

# Model Architecture
1. Artificial Neural Network (ANN)
2. Attention Mechanism for feature importance
3. Dense layers with ReLU activation
4. Dropout for regularization
   
#  Models Used
1. Logistic Regression
2. SVM
3. Decision Tree
4. KNN
5. Random Forest
6. ANN
7. ANN + Attention (Best Model)

# Results
1. Achieved **99%+ accuracy and F1-score**
2. ANN with Attention outperformed all baseline models
3. ROC AUC score close to 1.0 (near-perfect classification)

#  Key Contributions
1. Developed EEG-based learning analysis framework
2. Applied SMOTE + PCA for improved performance
3. Introduced attention-based neural model for better feature learning
4. Achieved highly reliable classification results
   
#  Tech Stack
1. Python
2. NumPy, Pandas
3. Scikit-learn
4. TensorFlow / Keras
5.  Matplotlib, Seaborn

#  Authors
This project is part of a collaborative research work conducted at SR University.

Ramesh Dadi 
Kanukuntla Shailaja
Vallala Vyshnavi

School of Computer Science and Artificial Intelligence  
SR University, Warangal, Telangana

# Kanukuntla Shailaja

Data preprocessing (missing value handling, normalization)
Class imbalance handling using SMOTE
Dimensionality reduction using PCA
Model training and performance evaluation
Experimental analysis and result interpretation

# Vallala Vyshnavi

Design and implementation of ANN architecture
Development of attention-enhanced ANN model
Model optimization and hyperparameter tuning
Integration of attention mechanism for feature importance
Analysis of model performance and improvements

# Ramesh Dadi

Project supervision and research guidance

##  How to Run
1. Open the `.ipynb` notebook
2. Run all cells step by step
3. Ensure required libraries are installed

##  Future Scope
1. Real-time EEG-based learning systems
2. Integration with e-learning platforms
3. Explainable AI for cognitive analysis

