# Image Forgery Detection Based on Fusion of Lightweight Deep Learning Models

## 📌 Overview
This project detects **forged images** by combining features from lightweight deep learning models and classifying them with an **SVM (Support Vector Machine)**.  
The fusion of **SqueezeNet, MobileNetV2, and ShuffleNet** achieves higher prediction accuracy compared to standalone models and traditional methods like **SIFT**.

---

## 🚀 Features
- Upload and preprocess **MICC-F220 Dataset** (Original + Forged images).  
- Normalize and resize all images for training.  
- Train **lightweight CNN models** (SqueezeNet, MobileNetV2, ShuffleNet).  
- Extract and fuse fine-tuned features from CNNs.  
- Train **SVM classifier** on fused features for forgery detection.  
- Compare results with baseline **SIFT + SVM** method.  
- Visualize results with **Confusion Matrix, Accuracy Graph, and Performance Table**.

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Deep Learning Models**: SqueezeNet, MobileNetV2, ShuffleNet  
- **Machine Learning**: SVM (scikit-learn)  
- **Image Processing**: OpenCV, NumPy, PIL  
- **Visualization**: Matplotlib, Seaborn  

---
