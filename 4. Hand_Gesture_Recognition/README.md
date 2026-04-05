# ✋ Hand Gesture Recognition using Machine Learning

## 📌 Overview
This project is a simple yet effective implementation of a **Hand Gesture Recognition System** using machine learning. It focuses on identifying different hand gestures from images and classifying them into predefined categories.

The system uses a **Support Vector Machine (SVM)** model trained on processed image data. This project demonstrates how image preprocessing and classical ML models can be combined to solve real-world computer vision problems.

---

## 🎯 Objective
- Recognize hand gestures from image data  
- Build a classification model using SVM  
- Understand the ML pipeline (preprocessing → training → prediction)  
- Apply machine learning to computer vision tasks  

---

## 🚀 Key Features
- Image preprocessing using OpenCV  
- Grayscale conversion and resizing  
- Feature extraction using flattened image vectors  
- SVM-based classification  
- Model evaluation using accuracy and classification report  
- Prediction on new/unseen images  

---

## 🗂️ Dataset
The dataset is sourced from kaggle.
from here: https://www.kaggle.com/gti-upm/leapgestrecog
The dataset is organized in folders where each folder represents a gesture class.

Example:
data/
├── gesture_1/
├── gesture_2/
└── gesture_3/

---

## ⚙️ Workflow

### 1. Data Loading
- Images are loaded from directories  
- Labels are assigned automatically  

### 2. Preprocessing
- Convert images to grayscale  
- Resize to 32×32  
- Normalize pixel values  

### 3. Feature Extraction
- Flatten images into 1D vectors  

### 4. Model Training
- Train using Support Vector Machine (SVM)  

### 5. Evaluation
- Accuracy score  
- Classification report  

### 6. Prediction
- Predict gesture for new input images  

---

## 🧠 Model Details
- Algorithm: Support Vector Machine (SVM)  
- Kernel: Linear  
- Input: Flattened image vectors  
- Output: Gesture label  

---

## 📊 Results
The model achieves good accuracy for basic gesture recognition tasks. Some confusion may occur between similar gestures, which can be improved with better data or advanced models.

---

## 🛠️ Tech Stack
- Python  
- OpenCV  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 💡 Future Improvements
- Use Convolutional Neural Networks (CNNs)
- Add real-time gesture detection
- Improve dataset quality and size
- Optimize model performance


---

## ⚙️ Workflow

### 1. Data Loading
- Images are loaded from directories  
- Labels are assigned automatically  

### 2. Preprocessing
- Convert images to grayscale  
- Resize to 32×32  
- Normalize pixel values  

### 3. Feature Extraction
- Flatten images into 1D vectors  

### 4. Model Training
- Train using Support Vector Machine (SVM)  

### 5. Evaluation
- Accuracy score  
- Classification report  

### 6. Prediction
- Predict gesture for new input images  

---

## 🧠 Model Details
- Algorithm: Support Vector Machine (SVM)  
- Kernel: Linear  
- Input: Flattened image vectors  
- Output: Gesture label  

---

## 📊 Results
The model achieves good accuracy for basic gesture recognition tasks. Some confusion may occur between similar gestures, which can be improved with better data or advanced models.

---

## 🛠️ Tech Stack
- Python  
- OpenCV  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 🙌 Learnings
- Image preprocessing techniques
- Machine learning model training
- Working with real-world datasets
- Building an end-to-end ML pipeline

---

## ⭐ Final Note

This project shows how traditional machine learning methods like SVM can effectively handle image classification tasks when combined with proper preprocessing.