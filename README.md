# MLP from Scratch (NumPy)

A multi-layer perceptron built with NumPy only: forward pass, backpropagation
and mini-batch SGD, trained on MNIST.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/mlp-from-scratch-numpy/blob/main/MLP_from_Scratch_NumPy.ipynb)

## Results
| Metric | Value |
|---|---|
| NumPy test accuracy | XX.XX% |
| PyTorch test accuracy | XX.XX% |
| Gradient check max relative error | X.Xe-XX |
| Max gradient difference vs PyTorch | X.Xe-XX |

## Architecture
784 → 256 → 128 → 10, ReLU, softmax cross-entropy, He init,
SGD (lr 0.1, batch 128, 15 epochs)

## What I built
- Dense and ReLU layers with hand-written backward passes
- Numerical gradient checking
- Training curves, confusion matrix, error analysis
- Comparison against an equivalent PyTorch model

Tech: Python, NumPy, PyTorch, MNIST
