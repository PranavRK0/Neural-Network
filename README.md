# Simple Neural Network Implementation from Scratch  

This repository contains a complete implementation of a simple neural network built from the ground up using NumPy. The project focuses on understanding the foundational principles of neural networks, including forward propagation, backpropagation, and gradient descent, without relying on external deep learning libraries.  

---

## Neural Network Architecture  
- **Inputs:** 2 features per data point.  
- **Hidden Layer:** 1 layer with 2 neurons.  
- **Output Layer:** 1 neuron for binary classification.  

---

## Key Features  
- **Activation Function:** Implements sigmoid and its derivative for activations.  
- **Loss Function:** Uses Mean Squared Error (MSE) for evaluating predictions.  
- **Training:**  
  - Gradient-based weight and bias updates via backpropagation.  
  - Supports configurable learning rate and number of epochs.  
- **Predictions:** Demonstrates the ability to predict outputs for unseen data.  

---

## Example Dataset  
The neural network is trained on a small dataset with labeled binary outputs. Example use cases include predicting outcomes based on the input features:  

### Example Inputs  
- Alice: `[-2, -1]`  
- Bob: `[25, 6]`  

### Example Outputs  
- Alice: `1` (class 1)  
- Bob: `0` (class 0)  

---
