# Brain_Tumor_Detection--Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision

## 📌 Project Overview
This project focuses on detecting and classifying **brain tumors from MRI images** using **Deep Learning and Computer Vision** techniques.  
A **Convolutional Neural Network (CNN)** model is used to automatically identify whether an MRI scan contains a tumor and determine its type.

The system aims to assist medical professionals by providing a **computer-aided diagnosis (CAD)** solution.

---

## 🎯 Objectives
- Detect brain tumors from MRI images
- Classify different types of brain tumors
- Reduce human error in manual diagnosis
- Apply deep learning concepts to medical imaging

---

## 🧠 Tumor Classes
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor (Healthy)

---

## 🗂 Dataset
- MRI Brain Images Dataset
- Image format: JPG / PNG
- Total Classes: 4
- Dataset is divided into:
  - Training set
  - Validation set
  - Testing set

### Preprocessing
- Image resizing
- Normalization
- Data augmentation (rotation, flip, zoom)

---

## ⚙️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **Deep Learning**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**

---

## 🏗 Model Architecture
- Input Layer (MRI Image)
- Convolutional Layers + ReLU
- Max Pooling Layers
- Dropout Layers
- Fully Connected Dense Layers
- Softmax Output Layer

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🚀 Workflow
1. Load MRI dataset
2. Preprocess images
3. Apply data augmentation
4. Build CNN model
5. Train the model
6. Evaluate performance
7. Predict tumor type on new MRI images

python main.py
