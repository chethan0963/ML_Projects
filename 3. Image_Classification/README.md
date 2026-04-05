# 🐱🐶 Cats vs Dogs Image Classification

## 📌 Overview
This project is an end-to-end Machine Learning pipeline built to classify images of cats and dogs. It focuses on understanding how traditional ML techniques can be applied to image data by converting images into numerical features.

The project walks through the full workflow — from data extraction and preprocessing to visualization and model building — making it a solid foundation for computer vision concepts.

---

## 📁 Dataset
The dataset is sourced from Kaggle.
from here: https://www.kaggle.com/c/dogs-vs-cats/data
The dataset consists of labeled images of cats and dogs, organized into:
- `train/`
- `test/`

---

## 🚀 Features
- 📦 Extracts and organizes dataset from ZIP files  
- 🖼️ Loads and preprocesses images (resizing & normalization)  
- 🔢 Converts images into flattened feature vectors  
- ⚖️ Applies feature scaling using StandardScaler  
- 📉 Visualizes high-dimensional data using t-SNE  
- 🤖 Implements a Support Vector Machine (SVM) classifier  
- 📊 Displays sample images and class distributions  

---

## 🛠️ Tech Stack
- **Python**
- **NumPy & Pandas** – Data manipulation  
- **OpenCV (cv2)** – Image processing  
- **Matplotlib** – Data visualization  
- **Scikit-learn** – Machine learning tools  

---

## 📂 Project Workflow

### 1. Data Extraction
The dataset is extracted from compressed ZIP files and organized into training and testing directories.

### 2. Image Loading & Preprocessing
Images are loaded using OpenCV, resized to a fixed dimension (64×64), and labeled:
- `0 → Cat`
- `1 → Dog`

### 3. Data Visualization
Sample images are displayed in a grid format to verify correctness and ensure proper labeling.

### 4. Feature Engineering
- Pixel values are normalized (0–255 → 0–1)  
- Images are flattened into 1D vectors for model compatibility  

### 5. Feature Scaling
StandardScaler is applied to standardize the dataset, improving model performance.

### 6. Dimensionality Reduction
t-SNE is used to reduce high-dimensional data into 2D space, helping visualize how well the classes are separated.

### 7. Model Training
The dataset is split into training and validation sets, and an SVM classifier is trained on the processed data.

### 8. Evaluation
The model is used to make predictions on unseen data. (Evaluation metrics can be extended further.)

---

## 📊 Results & Insights
- The model is able to learn distinguishable patterns between cats and dogs  
- t-SNE visualization shows partial clustering of the two classes  
- Performance can be improved with better feature extraction or deep learning models  

---

## 📌 Current Status
✔ Data preprocessing pipeline completed  
✔ Feature engineering and scaling implemented  
✔ t-SNE visualization working  
✔ Basic ML model pipeline created  

⚠️ Model evaluation and optimization are in progress  
⚠️ Minor bugs (like PCA usage) need refinement  

---

## 🚧 Work in Progress
- [ ] Fix and properly integrate PCA  
- [ ] Add evaluation metrics (Accuracy, Precision, Recall, F1-score)  
- [ ] Implement confusion matrix visualization  
- [ ] Perform hyperparameter tuning  
- [ ] Improve preprocessing efficiency  
- [ ] Add model saving/loading (joblib)  
- [ ] Experiment with CNN (Deep Learning approach)  
- [ ] Deploy using Streamlit or Flask  


---

## 💡 Key Learnings
- Handling and preprocessing image data using OpenCV  
- Applying Machine Learning models to image-based problems  
- Understanding the importance of scaling and feature transformation  
- Visualizing high-dimensional data using t-SNE  
- Building a structured ML pipeline from scratch  

---

## 🎯 Future Scope
This project can be extended into a more advanced computer vision system by:

- Implementing Convolutional Neural Networks (CNNs)  
- Using transfer learning (e.g., ResNet, VGG)  
- Building a real-time prediction application  
- Deploying the model as a web application  

---

## 🙌 Acknowledgements
- Scikit-learn documentation  
- OpenCV community  
- Public Cats vs Dogs dataset  

---

## ✨ Author
Chethan