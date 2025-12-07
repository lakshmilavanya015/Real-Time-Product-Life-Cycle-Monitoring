

# 🚀 Real-Time Product Life Cycle Monitoring 

A machine learning–powered system designed to **monitor, analyze, and predict the complete life cycle of a product** — from production to usage, maintenance, and end-of-life.  
The project also includes **real-time anomaly detection**, **status prediction**, and a **FastAPI-based monitoring API** suitable for dashboards or live analytics systems.

---

## 📌 Features

### ✔️ 1. Real-Time Life Cycle Monitoring  
Tracks product parameters (temperature, vibration, voltage, usage hours) and predicts the current product stage:
- Production  
- Usage  
- Maintenance  
- End of Life  

### ✔️ 2. ML-Based Life Cycle Status Prediction  
Uses a **Random Forest Classifier** to predict product life-cycle stages.

### ✔️ 3. Anomaly Detection
Two anomaly detection approaches:
- **Isolation Forest (Sklearn)**  
- **Autoencoder-based Deep Learning (TensorFlow)** *(optional)*  

Detects abnormal behavior early to reduce downtime and improve reliability.

### ✔️ 4. FastAPI Real-Time Monitoring API  
Includes endpoints for:
- `/predict` → Returns life-cycle prediction + anomaly status  
- `/live_data` → Provides recent product metrics for dashboards  
- `/` → API health check  

### ✔️ 5. Dashboard-Friendly  
API responses are structured for easy integration with:
- Web dashboards  
- BI tools (Tableau, Power BI)  
- IoT visualization platforms  

---

## 🧩 Tech Stack

| Component | Technology |
|----------|------------|
| Programming | Python |
| Machine Learning | Scikit-learn, TensorFlow (optional) |
| Data Handling | NumPy, Pandas |
| Backend API | FastAPI, Uvicorn |
| Models | RandomForestClassifier, IsolationForest, Autoencoder |

---

## 📂 Project Structure

