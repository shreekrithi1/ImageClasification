# CIFAR-10 Image Classification with Convolutional Neural Networks (CNN) in PyTorch

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Accuracy](https://img.shields.io/badge/Test%20Accuracy-78.3%25-brightgreen)

A complete, from-scratch implementation of an image classifier on the famous **CIFAR-10** dataset using only PyTorch and torchvision — no pre-trained models!

**Final Test Accuracy: ~78.3%** after training a small custom CNN from scratch.

![CIFAR-10 Samples](https://miro.medium.com/max/709/1*LyV7_xga4jUHdx4_jHk1PQ.png)

## 📊 CIFAR-10 Dataset

- 60,000 32×32 color images
- 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- 50,000 training images • 10,000 test images

## 🎯 What This Project Covers

- Downloading & extracting datasets from URLs
- Loading images with `torchvision.datasets.ImageFolder`
- Building a Convolutional Neural Network from scratch
- Training on GPU with automatic device handling
- Visualizing training/validation loss & accuracy
- Understanding underfitting vs overfitting
- Making predictions on single images
- Saving and loading model weights
- Clean, well-commented, beginner-friendly code

## 🚀 Results

| Metric             | Value      |
|--------------------|------------|
| Test Accuracy      | **78.28%** |
| Test Loss          | 0.821      |
| Training Time      | ~10–12 min on free Colab/Kaggle GPU |
| Model Size         | ~1.2 MB   |

Sample prediction:
