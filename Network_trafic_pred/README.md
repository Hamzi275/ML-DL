# 🌐 Network Traffic Prediction

A machine learning pipeline for forecasting **network traffic patterns**.  
The project leverages time-series data, preprocessing, and multiple ML models, culminating in a hybrid ensemble for improved accuracy and stability.

---

## 📊 Dataset
- Dataset: **Publicly available network traffic dataset**  
- Data represents real-world network usage patterns (timestamps, packets, bandwidth, etc.)  
- Preprocessing included handling missing intervals, noise reduction, and normalization.  

---

## 🔧 Workflow
1. **Data Preprocessing**  
   - Resampled data into fixed time intervals  
   - Removed anomalies & noise using statistical filters  
   - Normalized traffic values for stable model training  

2. **Feature Engineering**  
   - Lag features & rolling averages for time-series forecasting  
   - Extracted trend & seasonality components  

3. **Exploratory Analysis**  
   - Traffic trend visualization  
   - Peak/off-peak pattern analysis  
   - Correlation analysis between features  

---

## 🤖 Models Implemented
- Linear Regression (baseline)  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  
- LSTM (for sequential time-series modeling)  

➡️ **Hybrid Ensemble Model** combined best-performing regressors to achieve stable forecasts.  

---

## ✅ Evaluation
- Metrics: **MAE, RMSE, R²**  
- Comparative accuracy across 5 models + hybrid ensemble  
- Visualizations:  
  - Predicted vs. Actual traffic curves  
  - Error distribution plots  

**Result:**  
🚀 The Hybrid Model + LSTM achieved the most accurate and robust predictions.  

---

## 🚀 Usage
```bash
git clone https://github.com/Hamzi275/ML-DL.git
cd ML-DL/Network_Traffic_Prediction
pip install -r requirements.txt
jupyter notebook network_traffic_prediction.ipynb
