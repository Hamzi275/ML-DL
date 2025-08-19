# 🎯 Object Detection using CNN Architectures

Through this project, I **mastered Convolutional Neural Networks (CNNs) and their architectures**, applying them to a highly complex object detection dataset.  
The work demonstrates a strong command of CNN design, training, and evaluation — from early architectures like **LeNet** and **AlexNet** to modern deep networks like **ResNet, DenseNet, and VGG16**.  

---

## 📊 Dataset
- Source: [Tiny Object Detection – Kaggle](https://www.kaggle.com/datasets/kailaspsudheer/tiny-object-detection)  
- A **challenging dataset** with small-scale objects, high variability in background, orientation, and scale.  

---

## 🔧 Workflow
1. **Data Preprocessing**  
   - Image resizing & normalization  
   - Augmentation: flips, rotations, noise injection  

2. **Model Training & Benchmarking**  
   Implemented and compared almost all major CNNs for object detection:  
   - LeNet  
   - AlexNet  
   - ZFNet  
   - VGG16Net  
   - ResNet  
   - DenseNet  
   - GoogLeNet  

---

## 🤖 Results
- **VGG16** delivered the **best accuracy and stability** on this dataset.  
- Analysis highlighted strengths & weaknesses of shallow vs. deep CNNs.  
- Dataset complexity favored deeper architectures (VGG16, ResNet, DenseNet).  

---

## 📌 Client Requirement
Although frameworks like **YOLO** were planned, the **client requested evaluation strictly with CNN architectures**.  
Therefore, this project focused on mastering and comparing traditional CNNs instead of real-time detection models.  

---

## ✅ Evaluation
- Metrics: Accuracy, Precision, Recall, F1-score  
- Confusion matrices (per-class)  
- Training curves (loss vs. epochs, accuracy vs. epochs)  
- Comparative performance plots across all CNNs  

**Result:**  
🚀 **VGG16** emerged as the best-performing CNN for this dataset.  

---

## 🚀 Usage
```bash
git clone https://github.com/Hamzi275/ML-DL.git
cd ML-DL/Object_Detection
pip install -r requirements.txt
jupyter notebook object_detection.ipynb
