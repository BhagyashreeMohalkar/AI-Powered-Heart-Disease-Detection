# 🩺 AI-Powered Heart Disease Detection

A Machine Learning project that predicts the likelihood of heart disease using patient data. Built with **Python**, **Scikit-learn**, and **Flask**.

---

## 🚀 Overview
This project analyzes medical data to detect heart disease early using AI models. It includes preprocessing, model training, evaluation, and a web app for live predictions.

---

## 📊 Dataset
- Source: UCI Heart Disease Dataset  
- Features: age, sex, chest pain, cholesterol, blood pressure, heart rate, etc.  
- Target: 0 = No Disease, 1 = Disease  

---

## 🧠 ML Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine  

The best-performing model is saved as **`model.pkl`**.

---

## ⚙️ How to Run
```bash
git clone https://github.com/BhagyashreeMohalkar/AI-Powered-Heart-Disease-Detection.git
cd AI-Powered-Heart-Disease-Detection
pip install -r requirements.txt
python app.py

## 📈 Results
- **Accuracy:** ~92% (Random Forest)
- **Evaluation Metrics:** Precision, Recall, F1-Score, ROC-AUC

---

## 🔮 Future Enhancements
- Add Explainable AI (SHAP/LIME)
- Deploy on Cloud (AWS/Heroku)
- Extend dataset for better generalization

---

## 📂 Folder Structure
├─ app.py
├─ cleaning_data.ipynb
├─ model_training.ipynb
├─ heart_disease_uci.csv
├─ heart_disease_uci_cleaned_dataset.csv
├─ model.pkl
├─ requirements.txt
└─ README.md
