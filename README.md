# Kassymbekov_Merekeyev_DL_Project

# Deep Learning Course Project: Drone Vision System


**Team Members:** * **Alikhan Kassymbekov** (ID: IT-2307)
* **Mertay Merekeyev** (ID: IT-2307)

![Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Framework](https://img.shields.io/badge/Framework-PyTorch%20%7C%20NumPy-orange)

---

## Project Overview

This repository contains the coursework for the Deep Learning project. The objective was to build a computer vision pipeline for **UAV (Drone) Object Detection**, progressing from mathematical foundations to modern architectures.

The project is organized into four progressive sections:
1.  **Section 1: Foundations:** Building a Multi-Layer Perceptron (MLP) from scratch using only `numpy`.
2.  **Section 2: Optimization:** Implementing advanced optimizers (Adam, RMSprop) and performing mathematical gradient checking.
3.  **Section 3: CNN Implementation:** A custom Convolutional Neural Network built purely in `numpy` (no deep learning frameworks) for low-level understanding.
4.  **Section 4: Modern Architectures:** Transfer Learning using **ResNet18** (PyTorch) on drone imagery (VisDrone/CIFAR-10) with custom data augmentation.

---

## Repository Structure

```text
├── Drone_Section_1_Foundations_of_Deep_Learning.ipynb  # MLP, Activations, Regression
├── Drone_Section_2_Optimization.ipynb                  # Adam/RMSprop, Gradient Check
├── Drone_Section_3_CNN_NumPy.ipynb                     # Pure NumPy CNN (Manual Backprop)
├── Drone_Section_4_ResNet_TransferLearning.ipynb       # PyTorch ResNet & VisDrone
├── Supplementary_Materials_Section1/                   # Saved weights & plots for Sec 1
├── Supplementary_Materials_Section2/                   # Saved weights & plots for Sec 2
├── Supplementary_Materials_Section3/                   # Saved weights & plots for Sec 3
├── Supplementary_Materials_Section4/                   # Saved weights & plots for Sec 4
├── requirements.txt                                    # Python dependencies
└── README.md                                           # Project Documentation
