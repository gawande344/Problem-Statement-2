# Problem-Statement-2
# MNIST Neural Network and Visualization

## Description
This project implements a neural network for classifying handwritten digits from the MNIST dataset using PyTorch. It also includes an interactive visualization interface using Gradio.

## Requirements
- Python 3
- PyTorch
- torchvision
- Gradio

## Installation
1. Install the required libraries:
    ```bash
    pip install torch torchvision gradio
    ```

## Usage
1. Train and evaluate the neural network:
    ```bash
    python train_evaluate.py
    ```

2. Launch the interactive visualization:
    ```bash
    python visualize.py
    ```

## Output
The training script will print the training loss and evaluation accuracy. The visualization interface allows users to draw digits and see the model's predictions.

## Visualization Features
- Visualize the weights of the first layer and how they change during training.
- Input custom digit images and see the model’s predictions.
