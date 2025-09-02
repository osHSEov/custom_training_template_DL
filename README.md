# PyTorch Training Template

A flexible and modular PyTorch training template for deep learning tasks, designed to streamline model training, evaluation, and visualization. This template supports mixed precision training, checkpointing, early stopping, and customizable metrics, making it suitable for a variety of machine learning projects.

## Features

* Modular Data Handling: Move data (tensors, lists, or dictionaries) to GPU/CPU with a single move_to_device function.
* Checkpointing: Save and load model, optimizer, and scheduler states for resuming training.
* Mixed Precision Training: Support for Automatic Mixed Precision (AMP) to optimize training on GPUs.
* Flexible Training Loop: Customizable loss functions, metrics, and improvement criteria.
* Early Stopping: Stop training if the model stops improving after a specified number of epochs.
* Visualization: Plot training and validation loss/metric curves using Matplotlib.
* Example Included: A simple Convolutional Neural Network (CNN) trained on the MNIST dataset.


