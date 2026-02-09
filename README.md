# 🔐 PhishGuard – Phishing URL Detection Web App

PhishGuard is an end-to-end **machine learning–powered web application** that detects whether a given URL is **phishing or legitimate**.  
The project covers the complete ML lifecycle — **data preprocessing, model training, evaluation, persistence, and web integration**.

---

## 🚀 Features
- Detects phishing URLs in real time
- Machine Learning–based classification
- REST API / Web UI integration
- Clear confidence & probability output
- Clean and modular project structure

---

## 🧠 Machine Learning Model

### Dataset Used
- **Phishing_Legitimate_full.csv**
- Contains pre-engineered numerical URL features
- Binary labels:
  - `0` → Legitimate
  - `1` → Phishing

### Algorithm
- **Random Forest Classifier (scikit-learn)**  
- Chosen for:
  - High accuracy
  - Robustness to noise
  - No need for feature scaling

---

## 📊 Model Performance

- **Accuracy:** **98%**
- **Evaluation Metrics Used:**
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC Curve & AUC

### Confusion Matrix
<img width="845" height="670" alt="confusionmatric" src="https://github.com/user-attachments/assets/1ba57b0f-942a-4945-996b-248338633e88" />


### Classification Report
<img width="1032" height="677" alt="heatmap" src="https://github.com/user-attachments/assets/4b3ca819-8b5e-4762-a7f4-df080aa7341e" />


### ROC Curve
<img width="887" height="661" alt="roc curve" src="https://github.com/user-attachments/assets/58df63b1-1494-43e5-8ed0-eef603f0f97e" />


> The model shows strong recall for phishing URLs, ensuring minimal false negatives.

---

## 🏗️ Model Training Workflow

```text
Dataset
   ↓
Feature Selection
   ↓
Train / Test Split
   ↓
Random Forest Training
   ↓
Model Evaluation
   ↓
Model Persistence (.pkl)

## 📸 Project Screenshots

### Home Page
<img width="1864" height="887" alt="home" src="https://github.com/user-attachments/assets/30061677-0ce8-4877-8e1a-5220bb984c88" />

### Risk Score Result
<img width="1864" height="887" alt="riskscore" src="https://github.com/user-attachments/assets/681cb098-0eec-4fbe-befb-a7376c4b6edf" />

### Technical Analysis
<img width="1864" height="887" alt="techanalysis" src="https://github.com/user-attachments/assets/47610774-e175-4160-a10a-2f793f70a1d7" />

### Security features
<img width="1864" height="887" alt="securityfeatures" src="https://github.com/user-attachments/assets/23b11431-7ced-4a82-a469-8116bbdf1c03" />
