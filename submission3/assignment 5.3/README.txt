
Assignment 5.3 – Fully Connected Neural Network (FCNN)
====================================================

Project Title:
Fully Connected Neural Network for Human Activity Recognition (WISDM Dataset)

----------------------------------------------------
Dataset
----------------------------------------------------
Dataset Name:
WISDM (Wireless Sensor Data Mining) Activity Recognition Dataset

File Used:
features.csv

Description:
The dataset contains preprocessed statistical features extracted from smartphone
accelerometer data. Each sample corresponds to a labeled human activity such as
walking, jogging, sitting, standing, etc.

----------------------------------------------------
Model Description
----------------------------------------------------
Model Type:
Fully Connected Neural Network (Multilayer Perceptron)

Architecture:
- Input Layer: Number of features from dataset
- Hidden Layer 1: 128 neurons, ReLU activation
- Hidden Layer 2: 64 neurons, ReLU activation
- Hidden Layer 3: 32 neurons, ReLU activation
- Output Layer: Softmax (multi-class classification)

Loss Function:
Cross-Entropy Loss

Optimizer:
Adam Optimizer

Training Epochs:
50

----------------------------------------------------
Evaluation Metrics
----------------------------------------------------
- Accuracy
- F1 Score (Weighted)
- Confusion Matrix
- Training vs Validation Loss Curves

----------------------------------------------------
How to Run the Code
----------------------------------------------------
1. Place 'features.csv' in the same directory as the notebook.
2. Open the provided Jupyter notebook (.ipynb).
3. Run all cells from top to bottom.
4. The notebook will automatically:
   - Load and preprocess the data
   - Train the FCNN model
   - Evaluate performance
   - Display plots and metrics

----------------------------------------------------
Comparison with Classical ML
----------------------------------------------------
The FCNN results are compared with a classical machine learning baseline
(Logistic Regression) from Deliverable 5.2. The FCNN demonstrates improved
performance due to its ability to model non-linear feature relationships.

----------------------------------------------------
Notes
----------------------------------------------------
- Label column is detected automatically.
- Feature scaling is applied using StandardScaler.
- The code is fully reproducible.

----------------------------------------------------
Author:
Student Name: ____________________
Course: __________________________
