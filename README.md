# 🧠 Brain Tumor Detection using SVM
## 📌 Overview
This project focuses on detecting and classifying brain tumors from MRI images using **Machine Learning techniques**.  
A **Support Vector Machine (SVM)** classifier is used along with **Principal Component Analysis (PCA)** for dimensionality reduction.

The system helps in **early diagnosis of brain tumors**, reducing manual effort and improving accuracy.

## 🚀 Features
- 🧠 MRI-based brain tumor classification  
- ⚙️ PCA for dimensionality reduction  
- 🤖 SVM classifier for prediction  
- 📊 Supports 4 tumor classes:
  - No Tumor  
  - Pituitary Tumor  
  - Glioma Tumor  
  - Meningioma Tumor  
- 📈 Training & Testing performance evaluation  
- 🖼️ Visualization of predictions  

## 🛠️ Technologies Used
- Python 🐍  
- OpenCV  
- NumPy  
- Matplotlib  
- Scikit-learn  


## 📊 Results

- 📈 Training Accuracy: **96.47%**  
- 📉 Testing Accuracy: **83.10%**  

### 🔍 Analysis
- High training accuracy indicates strong learning  
- Slight overfitting observed  
- Some misclassification between similar tumor types  

## ⚠️ Limitations
- Loss of spatial features due to flattening  
- Dataset imbalance  
- Overfitting on training data  
- Similar tumor appearance in MRI images  


## How to Run
```bash
git clone https://github.com/your-username/brain-tumor-detection.git
cd brain-tumor-detection
