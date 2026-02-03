# PyTorch Fundamentals – Binary Classification

This repository demonstrates **core PyTorch fundamentals** by solving a **binary classification** problem on a synthetic non-linear dataset.

The project focuses on understanding how neural networks work **from scratch**, rather than relying on high-level abstractions.

## Notebook Overview

The notebook covers the full PyTorch workflow:

- Dataset creation and visualization
- Train / test split
- Tensor conversion and device handling (CPU / GPU)
- Custom neural network using `nn.Module`
- Loss functions and optimizers
- Manual training and evaluation loops
- Model evaluation and decision boundary visualization

## Dataset

A synthetic **non-linear binary classification dataset** is generated using `make_circles` from `scikit-learn`.

This dataset is ideal for demonstrating why:
- Linear models fail
- Non-linear activation functions (ReLU) are required

## Model Architecture

A simple feed-forward neural network:

- Input layer: 2 features
- Hidden layers with ReLU activation
- Output layer: 1 neuron (binary classification)
- Loss function: `BCEWithLogitsLoss`
- Optimizer: Adam

## Results

- The model successfully learns a **non-linear decision boundary**
- High accuracy on both training and test sets
- Clear visualization of learned decision regions

## How to Run

# 1. Clone the repository:

```bash
git clone https://github.com/yourusername/pytorch-fundamentals.git
```

# 2. Install dependencies:
pip install -r requirements.txt

# 3. Open the notebook::
notebooks/pytorch_binary_classification_circles.ipynb

# Developed by Blagoja Budzakoski