# Multiclass_Image_Classifier
# 🐾 Animal Image Classification using CNN (Sequential Model)

## 📌 Project Overview
This project focuses on building a **custom image classification system** using a **Convolutional Neural Network (CNN) with a Sequential architecture**.  
The model classifies images into **five animal classes**: **Dog, Cow, Cat, Lamb, and Zebra**.

A custom dataset was created with **100 images per class**, collected from the internet and real-world captures.  
The trained model achieves **at least 90% classification accuracy**.

---

## 🎯 Objectives
- Create a **custom image dataset** with five animal categories  
- Design and train a **CNN Sequential model**
- Achieve **≥ 90% accuracy**
- Evaluate model performance using validation and test data

---

## 🗂 Dataset Details
- **Classes**:
  - Dog
  - Cow
  - Cat
  - Lamb
  - Zebra
- **Images per class**: 100  
- **Total images**: 500
- **Image source**: Internet + mobile phone camera
- **Image size**: Resized to a fixed resolution before training

### Dataset Structure
```
dataset/
├── dog/
├── cow/
├── cat/
├── lamb/
└── zebra/
```





---

## 🧠 Model Architecture
The model is built using **Keras Sequential API** with the following layers:

- Convolutional layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Fully connected (Dense) layers for classification
- Softmax activation for multi-class prediction

### Why CNN Sequential?
- Simple and easy to understand
- Effective for image classification tasks
- Suitable for small-to-medium datasets

---

## ⚙️ Training Configuration
- **Framework**: TensorFlow / Keras
- **Model Type**: CNN (Sequential)
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Epochs**: 20
- **Batch Size**: 32
- **Image Size**: 256 × 256

---

## 📊 Results
- **Training Accuracy**: 100%
- **Validation Accuracy**: 100%
- The model successfully distinguishes between all five animal classes.

---

## 🧪 Testing & Prediction
The trained model can predict the class of a **new unseen image** and output the **predicted animal label**.


---

## 📦 Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

Install dependencies:
```bash
pip install tensorflow numpy matplotlib

