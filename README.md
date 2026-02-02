**Brain Tumor Detection using Deep Learning**

This project is a Deep Learning–based Brain Tumor Detection System that classifies MRI brain images into different tumor categories using transfer learning models.
**A Streamlit web application** is built on top of the trained model for real-time prediction.

**Project Overview**

Brain tumor diagnosis from MRI scans is a critical and time-sensitive task.
This project leverages Convolutional Neural Networks (CNNs) and pre-trained deep learning models to accurately classify MRI images into the following classes:
No Tumor
Glioma
Meningioma
Pituitary Tumor

Among multiple trained models, InceptionV3 achieved the best performance and is used in the deployed Streamlit application.

**Features**

Upload MRI brain images (JPG / PNG)

Deep learning–based tumor classification

Confidence score for predictions

Comparison of multiple CNN architectures

Interactive Streamlit web interface

Clean and modular codebase

**Models Used**

The following models were trained and evaluated:

| Model | Description |
|------|------------|
| Custom CNN | Baseline CNN built from scratch |
| MobileNet | Lightweight transfer learning model |
| ResNet50 | Deep residual network |
| EfficientNetB0 | Efficient scaling CNN |
| **InceptionV3 ⭐** | Best performing model |


**Best Model Selection**

InceptionV3 was chosen based on:

Highest test accuracy

Lowest test loss

Better generalization on unseen MRI images

## 📊 Model Performance

| Model | Test Accuracy (%) | Test Loss |
|-------|------------------|-----------|
| InceptionV3 | 87.39 | 0.36 |
| MobileNet | 80.89 | 0.66 |
| ResNet50 | 71.95 | 0.70 |
| Custom CNN (Baseline) | 70.73 | 0.71 |
| EfficientNetB0 | 32.52 | 1.36 |


**🏗️ Tech Stack**

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib / Seaborn

Streamlit

Transfer Learning

**Sample Output**

Uploaded MRI image preview

Predicted tumor type

Confidence score

Class-wise probability distribution

⚠️ Disclaimer:
This project is intended for educational and research purposes only and should not be used for medical diagnosis.

**Training Details**

Image Size: 299 × 299

Optimizer: Adam

Loss Function: Categorical Cross-Entropy

Callbacks Used:

ReduceLROnPlateau

EarlyStopping

ModelCheckpoint

Data Augmentation applied to training set

**Future Improvements**

Add Grad-CAM visual explanations

Improve dataset balance

Deploy on cloud (AWS / Hugging Face / Streamlit Cloud)

Add API support

Add model confidence thresholding



