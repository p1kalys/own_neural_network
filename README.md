# Own Neural Network (PyTorch)
This project demonstrates how to build a neural network from scratch using PyTorch, covering everything from architecture definition to training and evaluation. It’s designed as a hands-on learning exercise for understanding the core building blocks of deep learning.

## Motivation

#### The goal of this project was to:

Learn the inner workings of neural networks by implementing one without high-level abstractions.

Understand how layers, activations, and backpropagation interact in training.

Explore how PyTorch simplifies tensor operations, GPU utilization, and gradient tracking.

By coding each component explicitly, this project bridges theory and practice.

## Implementation

Dataset → (Replace with your dataset, e.g., MNIST, CIFAR-10, custom synthetic data).

Architecture → Defined as a custom PyTorch model using torch.nn.Module, including layers, activation functions, and forward propagation logic.

Training loop → Implemented manually with batching, loss calculation, backpropagation (loss.backward()), and optimizer steps.

Evaluation → Accuracy and/or loss plotted across epochs, showing convergence and generalization.

Extras → Visualization of results and intermediate outputs to validate learning.

## Technologies Used & Why

PyTorch → Chosen for its dynamic computation graph and beginner-friendly API.

Jupyter Notebook → For step-by-step execution, experimentation, and inline visualization.

NumPy → Data manipulation and matrix operations.

Matplotlib/Seaborn → Plotting training curves and metrics.

🔄 Alternatives:

Could also be implemented in TensorFlow/Keras for more declarative training, or even pure NumPy for maximum transparency.
