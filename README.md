# CodeAlpha_Handwritten_Digit_Recognition (CNN)

# Objective
To build a Convolutional Neural Network (CNN) model capable of recognizing handwritten digits (0–9) using the MNIST dataset.

# Dataset
Source: MNIST dataset (built into TensorFlow/Keras)
Training samples: 60,000
Testing samples: 10,000
Image size: 28 × 28 pixels (grayscale)
Classes: Digits 0 to 9

# Technologies Used
Language: Python
Framework: TensorFlow / Keras
Libraries: NumPy, Matplotlib, scikit-learn
Environment: Google Colab (GPU enabled)

# Steps Followed
1-Data Loading & Visualization — Loaded MNIST and displayed sample digits.
2-Preprocessing — Normalized pixel values (0–1), reshaped input (28×28×1), and split data into train/validation/test.
3-Model Building — Created a CNN with:
    Conv2D, MaxPooling2D layers
    Dense layers with ReLU and Dropout
    Output layer using Softmax (10 classes)
4-Training — Used EarlyStopping, ModelCheckpoint, and ReduceLROnPlateau callbacks for efficient learning.
5-Evaluation — Achieved 99% accuracy on test data.
6-Visualization — Plotted accuracy/loss curves and analyzed misclassified images.

# Results
Training Accuracy :	99.5%
Validation Accuracy :	99.0%
Test Accuracy	: 99.0%
Loss (Test) :	~0.04

# Conclusion:
The CNN model successfully recognizes handwritten digits with ~99% accuracy and excellent generalization on unseen data.
