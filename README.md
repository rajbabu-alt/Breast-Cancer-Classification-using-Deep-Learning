# Breast-Cancer-Classification-using-Deep-Learning
This project implements a neural network model to classify breast cancer cases using the Wisconsin Breast Cancer Diagnostic dataset. The model is built with Keras and TensorFlow.

Overview
The notebook follows a standard machine learning workflow:

Data Loading: Uses the load_breast_cancer dataset from sklearn.

Preprocessing: Includes feature scaling using StandardScaler and splitting the data into training and testing sets (80/20 split).

Model Architecture: A Sequential neural network with three Dense layers.

Training: The model is trained for 50 epochs with a validation split.

Model Architecture
The model is a Sequential network consisting of:

Input Layer: 30 features.

Hidden Layer 1: 16 neurons with ReLU activation.

Hidden Layer 2: 8 neurons with ReLU activation.

Output Layer: 1 neuron with Sigmoid activation (suitable for binary classification).


Compilation Settings:

Optimizer: Adam.

Loss Function: Binary Crossentropy.

Metrics: Accuracy.



