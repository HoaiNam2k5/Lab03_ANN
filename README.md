# Lab03_ANN - Artificial Neural Network

**Student:** Nguyễn Hoài Nam  
**Student ID:** 2001230530

## Overview

This repository contains Lab 03 notebooks for building and evaluating **Artificial Neural Network (ANN)** models on:

- **MNIST** (handwritten digit recognition)
- **CIFAR-10** (image classification with 10 classes)

The notebooks cover the full workflow: data loading, preprocessing, ANN model building, training, and evaluation.

## Repository Structure

- `/home/runner/work/Lab03_ANN/Lab03_ANN/ANN_MNIST.ipynb`  
  ANN for handwritten digit recognition on MNIST.
- `/home/runner/work/Lab03_ANN/Lab03_ANN/ANN_CIFAR10_Lab03.ipynb`  
  ANN for CIFAR-10 image classification.

## Main Topics in the Lab

- Import and configure ML libraries
- Load datasets from Keras (with fallback options in MNIST notebook)
- Explore and visualize samples
- Preprocess input data for ANN
- Build ANN models with TensorFlow/Keras
- Train and validate models
- Evaluate with classification metrics and confusion matrix

## Requirements

Suggested Python packages:

- `tensorflow`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `pandas`
- `Pillow`
- `jupyter`

## How to Run

1. Open Jupyter Notebook or Google Colab.
2. Open one of the notebooks:
   - `ANN_MNIST.ipynb`
   - `ANN_CIFAR10_Lab03.ipynb`
3. Run all cells from top to bottom.

## Notes

- MNIST notebook supports loading data from a local teacher-provided file or Keras fallback.
- CIFAR-10 notebook uses `tensorflow.keras.datasets.cifar10`.
