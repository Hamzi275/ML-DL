# 🏡 House Price Prediction

A robust machine learning pipeline to predict house prices.  
We tackled a noisy dataset, applied advanced preprocessing, and built multiple ML models, followed by a **hybrid ensemble** that delivered the best performance.

---

## 📊 Dataset
- **Private dataset** (not publicly available).  
- Data contained heavy noise → cleaned using robust preprocessing techniques.  

---

## 🔧 Workflow
1. **Data Cleaning & Preprocessing**  
   - Outlier handling & missing values treatment  
   - Feature scaling & encoding  
   - Noise reduction with statistical + ML-based methods  

2. **Feature Selection**  
   - Applied **Feature Importance Scoring (FIS)**  
   - Retained most predictive features  

3. **Exploratory Analysis**  
   - Distribution plots  
   - Correlation heatmaps  
   - Feature impact visualizations  

---

## 🤖 Models Implemented
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  

➡️ **Hybrid Ensemble Model** built from best performers for superior accuracy.  

---

## ✅ Evaluation
- **Accuracy, Loss Curves** for each model  
- **Confusion Matrix** (on discretized prices for interpretability)  
- Comparative visualization of all 5 models + Hybrid  

**Result:**  
🚀 The Hybrid Model outperformed individual learners with higher stability and prediction accuracy.  

---

## 🚀 Usage
```bash
git clone https://github.com/Hamzi275/ML-DL.git
cd ML-DL/House_Price_Prediction
pip install -r requirements.txt
jupyter notebook house_price_prediction.ipynb
