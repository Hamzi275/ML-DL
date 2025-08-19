# Deepfake Face Detection

This project focuses on detecting **real vs fake faces** using deep learning techniques.  
The model was trained on a large dataset of both genuine and artificially generated faces, achieving strong results in classification performance.

---

## Dataset

The dataset used for this project is available on Kaggle:  
👉 [140k Real and Fake Faces](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces)

It contains a balanced collection of real and fake face images, making it suitable for binary classification tasks.

---

## Approach

- **Data Preprocessing**  
  - Image resizing and normalization  
  - Train/test split  
  - Data augmentation to improve generalization  

- **Model Architecture**  
  - Deep Convolutional Neural Network (CNN)  
  - Used transfer learning (e.g., ResNet, EfficientNet, or VGG variants) for better performance  

- **Training**  
  - Optimizer: Adam  
  - Loss Function: Binary Cross-Entropy  
  - Evaluation Metrics: Accuracy, Precision, Recall, F1-score  

---

## Results

- Achieved **high accuracy** in distinguishing real vs fake faces.  
- Demonstrated robustness across different test samples.  
- The project shows the potential of DL-based models in tackling deepfake detection challenges.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Hamzi275/ML-DL.git
   cd ML-DL/Deepfake_detection
