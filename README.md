
## Overview

This code covers the fundamental task of text analysis and classification using **Artificial Neural Network (ANN)**

This implementation from scratch to build practical understanding of NLP concepts and algorithms helps in understanding the working of ANNs.

1. **Dataset Preparation:**
   - Loading and preprocessing the dataset, building a vocabulary and converting each review into one-hot encoded vectors.
2. **ANN Architecture:**
   - ANN with:
     - An input layer (size = vocabulary size).
     - A hidden layer (e.g., 128 or 256 neurons with ReLU/Sigmoid activation).
     - An output layer with a single neuron for binary classification.
   - Train the network using backpropagation.
3. **Evaluation:** Test the ANN on a separate test set and calculate accuracy, confusion matrix, precision, recall, and F1-score.
