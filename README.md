# Industrial Surface Crack Detection Using CNN

## 📌 Project Overview

Industrial Surface Crack Detection Using CNN is a Deep Learning based computer vision project developed to automatically identify cracks on industrial surfaces. The system uses a Convolutional Neural Network (CNN) to classify images into two categories:

* Crack
* No Crack

The model is trained on labeled industrial surface images and can be used for automated quality inspection in manufacturing industries.

---

## 🎯 Objectives

* Detect surface cracks automatically.
* Reduce manual inspection efforts.
* Improve industrial quality control.
* Achieve high accuracy using Deep Learning techniques.

---

## 🚀 Features

* Automatic dataset preprocessing
* Train, Validation, and Test dataset splitting
* Data augmentation for improved generalization
* Deep CNN architecture with Batch Normalization
* Early Stopping to prevent overfitting
* Model Checkpointing
* Learning Rate Reduction
* Accuracy and Loss Visualization
* Confusion Matrix Generation
* Classification Report
* Single Image Prediction
* Model Saving and Loading

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-Learn



## 🧠 CNN Architecture

The model consists of:

* Conv2D Layer (32 Filters)
* Batch Normalization
* Max Pooling
* Conv2D Layer (64 Filters)
* Batch Normalization
* Max Pooling
* Conv2D Layer (128 Filters)
* Batch Normalization
* Max Pooling
* Conv2D Layer (256 Filters)
* Batch Normalization
* Max Pooling
* Flatten Layer
* Dense Layer (256 Neurons)
* Dropout (0.5)
* Dense Layer (128 Neurons)
* Dropout (0.3)
* Output Layer (Sigmoid)

## 📊 Training Features

* Binary Classification
* Adam Optimizer
* Binary Crossentropy Loss
* Early Stopping
* Model Checkpoint
* Reduce Learning Rate on Plateau

---

## 📈 Performance Evaluation

The project evaluates performance using:

* Accuracy Score
* Loss Score
* Confusion Matrix
* Precision
* Recall
* F1 Score
* Classification Report

---

## 🔍 Single Image Prediction

The system can predict whether a single image contains a crack or not.

Example Output:

```text
Image Path       : sample.jpg
Prediction Value : 0.96
Final Result     : Crack Detected
```


## 🏭 Applications

* Manufacturing Industry
* Steel Surface Inspection
* Concrete Structure Monitoring
* Bridge Inspection
* Railway Track Monitoring
* Aerospace Component Inspection
* Industrial Quality Control

---

## 🔮 Future Enhancements

* Real-Time Crack Detection using Webcam
* Transfer Learning (ResNet, EfficientNet)
* Mobile Application Integration
* IoT-based Monitoring System
* Defect Localization with Object Detection
* Cloud Deployment

---

## 👨‍💻 Author

**Rushikesh Gade**

Artificial Intelligence | Deep Learning | Computer Vision Enthusiast

