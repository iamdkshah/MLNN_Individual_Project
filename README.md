# MLNN_Individual_Project
A deep learning project for brain tumour detection using CNNs and Grad-CAM
# Brain Tumor Detection Using Deep Learning

This project uses Convolutional Neural Networks (CNNs) and transfer learning to classify brain MRI images into four categories: **glioma**, **meningioma**, **pituitary tumor**, and **no tumor**. The best-performing model (EfficientNetB0) is fine-tuned, and Grad-CAM is used to interpret the model's predictions.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Repository Structure](#repository-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results](#results)
6. [License](#license)

---

## Project Overview

The goal of this project is to detect brain tumors in MRI images using deep learning. The project compares multiple CNN architectures (e.g., VGG16, ResNet50, EfficientNetB0) and fine-tunes the best-performing model. Grad-CAM is used to visualize the regions of the MRI images that the model focuses on when making predictions.

---

## Repository Structure
brain-tumor-detection/
├── data/ # Contains the dataset (Training and Testing folders)
├── models/ # Saved models (e.g., VGG16, EfficientNetB0)
├── scripts/ # Python scripts for training, evaluation, and Grad-CAM
│ ├── train.py # Script to train the models
│ ├── evaluate.py # Script to evaluate the models
│ └── grad_cam.py # Script to generate Grad-CAM heatmaps
├── requirements.txt # List of Python dependencies
└── README.md # This file

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/iamdkshah/MLNN_Individual_Project
   cd MLNN_Individual_Project
Download the Dataset:

Download the brain tumor dataset and place it in the data/ folder.

The dataset should have the following structure:
   
data/
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── pituitary/
│   └── no_tumor/
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── pituitary/
    └── no_tumor/
# Run the following command to train the models:
python scripts/train.py
# Evaluate the Models
python scripts/evaluate.py
# Generate Grad-CAM Heatmaps
python scripts/grad_cam.py
