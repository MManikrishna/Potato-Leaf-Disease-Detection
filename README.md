# Potato-Leaf-Disease-Detection
"Potato Disease Classification is a deep learning project using Convolutional Neural Networks (CNNs) to classify potato leaf images as healthy or diseased (Early Blight, Late Blight). It enables early detection of crop diseases, supporting farmers and smart agriculture solutions.”

# Potato Disease Classification

**Deep learning project for classifying potato leaf diseases using custom CNNs and pretrained VGG16 & VGG19 models.**  

This project automates the detection of potato leaf diseases from images, classifying leaves as **Healthy**, **Early Blight**, or **Late Blight**. Early detection helps farmers prevent crop loss and supports smart agriculture solutions.

---

## 🎯 Project Objective

- Build and train **custom CNN models** for image classification  
- Use **VGG16 & VGG19 pretrained models** for transfer learning  
- Compare performance of custom vs pretrained models  
- Provide an AI solution for early potato disease detection  

---

## 🗂 Dataset

- Labeled images of potato leaves:  
  - Healthy  
  - Early Blight  
  - Late Blight  
- Images were preprocessed: resized, normalized, and augmented for training  
- **Sample data included in `data/` folder**, full dataset download link provided in README

---

## 🧠 Models Used

1. **Custom CNN** – designed from scratch to classify leaf images  
2. **VGG16 & VGG19** – pretrained models used with transfer learning to improve accuracy  

Training involved fine-tuning the top layers while leveraging pretrained features from ImageNet.

---

## 🛠 Tools & Technologies

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- OpenCV  
- Matplotlib / Seaborn  

---

## 📊 Results

- Custom CNN achieved high accuracy on test data  
- VGG16 & VGG19 improved performance and reduced training time  
- Confusion matrices, accuracy/loss curves, and sample predictions included in notebooks  

---

## 📁 Project Structure

