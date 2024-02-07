# Artificial Neural Network (ANN) Implementation

## Overview
This Python script implements a simple Artificial Neural Network (ANN) using a feedforward architecture for binary classification. The ANN is trained using backpropagation with gradient descent as the optimization algorithm. The sigmoid activation function is used in the hidden layers, and the output layer uses a sigmoid activation function as well. 

## Code Description
1. **Activation Functions**: The script defines the sigmoid activation function and its derivative, which are used for the forward and backward propagation steps.
2. **Weight Initialization**: The `initialize_weights_and_biases` function initializes the weights and biases of the neural network based on the number of input features, hidden layers, and nodes per layer.
3. **Training Function**: The `train` function trains the neural network using the provided input data (features and labels). It implements forward and backward propagation to update the weights and biases iteratively.
4. **Input and Output Data**: The script defines sample input and output data for binary classification tasks.
5. **Main Execution**: The script executes the training function with the specified parameters and prints the binary classification output.

## How to Use
1. Define the input features (`X`) and corresponding labels (`y`) for your classification task.
2. Adjust the parameters such as the number of hidden layers and nodes per layer as needed.
3. Run the script, and the trained neural network will output the binary classification results based on the provided input data.

## Prerequisites
- Python 3.x
- Basic understanding of neural networks and backpropagation algorithm.

## Notes
- This implementation serves as a basic example of an ANN for binary classification tasks.
- You can customize the network architecture, activation functions, and optimization algorithm according to your requirements.
- For more complex tasks, consider using deep learning libraries such as TensorFlow or PyTorch.

Experiment with different network architectures and training parameters to optimize performance for your specific classification tasks.
