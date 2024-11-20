# PyTorch Classification Notebook

## Overview

This repository contains a PyTorch-based Jupyter Notebook that demonstrates how to structure and train deep learning models in a modularized way. It covers:

- Setting up a PyTorch environment
- Loading and preprocessing data
- Defining, training, and evaluating neural networks
- Organizing code into reusable modules
- Uses the models: EfficientNet B2, VisionTransformer, ResNet, SwinTransformer, DenseNet, VGG
## Features

### Modular Code Structure
The project uses a modular approach to enhance code reusability and maintainability. Key modules include:

- **Data Setup (`data_setup.py`)**: For loading and preprocessing datasets.
- **Training Engine (`engine.py`)**: Encapsulates the training and evaluation loops.
- **Utilities (`utils.py`)**: Helper functions for metrics, visualizations, and other utilities.

### Core Functionalities
1. **Data Loading**:
   - Fetch datasets using `download_data` and preprocess using PyTorch's `transforms`.
   - Datasets split into training and testing sets.

2. **Model Training**:
   - Train neural networks using `torch.nn.Module`.
   - Includes optimization, backpropagation, and loss computation.

3. **Performance Visualization**:
   - Plot training and evaluation metrics such as loss and accuracy.

4. **Version Checks**:
   - Ensures compatibility with required versions of PyTorch and TorchVision.

## Prerequisites

- Python 3.8 or higher
- PyTorch 1.12+ and TorchVision 0.13+
- Jupyter Notebook
- Other dependencies: `torchvision`, `matplotlib`, `pandas`, `tqdm`

Install all requirements with:

```bash
pip install torch torchvision matplotlib pandas tqdm
