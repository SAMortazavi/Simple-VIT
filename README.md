# Vision Transformer (ViT) Implementation and CIFAR-10 Testing

This repository contains a simple implementation of the Vision Transformer (ViT) architecture based on the seminal paper "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale" ([arXiv:2010.11929](https://doi.org/10.48550/arXiv.2010.11929)). The implementation has been tested on the CIFAR-10 dataset to demonstrate its effectiveness.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Repository Features](#repository-features)
3. [Requirements](#requirements)
4. [Acknowledgements](#acknowledgements)

---

## Introduction

The Vision Transformer (ViT) revolutionizes image classification by leveraging self-attention mechanisms, commonly used in natural language processing, for visual data. Instead of convolutions, ViT splits an image into fixed-size patches, linearly embeds them, and applies a Transformer encoder to extract meaningful features for classification.

This project implements a simple version of ViT and applies it to the CIFAR-10 dataset, a standard benchmark in computer vision. Despite its simplicity, the model achieves competitive results and highlights the power of transformer-based architectures in image recognition tasks.

---

## Repository Features

- Implementation of the Vision Transformer architecture from scratch.
- Training and evaluation on the CIFAR-10 dataset.
- Configurable hyperparameters (e.g., patch size, embedding dimension, number of Transformer layers).
- Comprehensive logging and visualization of training metrics.
- Lightweight and easy to extend for other datasets.

---

## Requirements

Ensure you have the following dependencies installed:

- Python 3.8+
- PyTorch 1.10+
- torchvision
- numpy
- matplotlib
- tqdm


## Acknowledgements

This implementation is inspired by the original ViT paper:

Dosovitskiy, A., Beyer, L., Kolesnikov, A., et al. (2020). "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale." [arXiv:2010.11929](https://doi.org/10.48550/arXiv.2010.11929).

The CIFAR-10 dataset is provided by the Canadian Institute for Advanced Research and can be found [here](https://www.cs.toronto.edu/~kriz/cifar.html).

---

Thank you for exploring this implementation! Contributions, suggestions, and feedback are welcome.

