# MLNN_Individual_Project
A deep learning project for brain tumour detection using CNNs and Grad-CAM
# Brain Tumor Detection Using Deep Learning

This project uses Convolutional Neural Networks (CNNs) and transfer learning to classify brain MRI images into four categories: **glioma**, **meningioma**, **pituitary tumor**, and **no tumor**. The best-performing model (EfficientNetB0) is fine-tuned, and Grad-CAM is used to interpret the model's predictions.

---

## Project Overview

The goal of this project is to detect brain tumors in MRI images using deep learning. The project compares multiple CNN architectures (e.g., VGG16, ResNet50, EfficientNetB0) and fine-tunes the best-performing model. Grad-CAM is used to visualize the regions of the MRI images that the model focuses on when making predictions.

---

# Brain Tumor Detection Tutorial
Compares transfer learning models and Grad-CAM for MRI tumor detection.
## Setup
1. Download MLNN_Individual_Project(5).ipynb (Google Colab Notebook)
2. Open and load this project, install TensorFlow, NumPy, etc., in Colab.
3. Download the dataset and upload `brain_tumor.zip` to Google Drive.
4. Run notebook cells.
## Dataset
Source: [https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri]. Structure: Training/[classes], Testing/[classes].
## License
MIT

## Installation

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

