# Potato Disease Classification

A deep learning project for classifying potato leaf images into **Healthy, Early Blight, and Late Blight** using Convolutional Neural Networks and transfer learning.

## Project Overview

Potato diseases can significantly affect crop production. This project uses deep learning-based image classification to identify common potato leaf diseases from images and support early disease detection.

## Project Objective

- classify potato leaf images into three categories:
  - Healthy
  - Early Blight
  - Late Blight
- Build and train a custom CNN model for image classification.
- Apply transfer learning using pretrained VGG16 and MobileNetV2 models.
- Compare model performance on the test dataset.
- Develop a model that can predict the disease category from a new leaf image.

## Dataset

The project uses a potato leaf image dataset containing three classes:

- **Healthy**
- **Early Blight**
- **Late Blight**

The images were resized and normalized before training. Data augmentation techniques were also applied to improve model generalization.

> The complete dataset is not included in this repository because of its size.

## Models Used

### 1. Custom CNNs

A Convolutional Neural Network was developed to learn visual features directly from potato leaf images.

### 2. VGG16

A pretrained VGG16 model was used with transfer learning to leverage features learned from ImageNet.

### 3. MobileNetV2

MobileNetV2 was used as another transfer-learning approach, providing a lightweight architecture suitable for image classification.

## Model Comparison

| Model | Test Accuracy |
|-------|---------------|
| Custom CNN | 89.43% |
| VGG16 | 87.13% |
| MobileNetV2 | 94.94% |

Based on the recorded test results, **MobileNetV2 achieved the highest test accuracy** among the evaluated models.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Seaborn
- Google Colab

## Project Workflow

```text
Potato Leaf Images
        ↓
Data Preprocessing
        ↓
Image Resizing & Normalization
        ↓
Data Augmentation
        ↓
Model Training
        ↓
Custom CNN / VGG16 / MobileNetV2
        ↓
Model Evaluation
        ↓
Disease Prediction
