# ❤️ Heart Disease Prediction using Logistic Regression

## 📌 Objective
This project predicts whether a person is at risk of **heart disease** based on 14 medical features (e.g., age, cholesterol, blood pressure).  
The model is built using **Logistic Regression** and evaluated with multiple metrics.

---

## 📊 Dataset
- **Source**: [Kaggle – Heart Disease UCI Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)  
- **Features**: 14 patient attributes (age, sex, chest pain type, cholesterol, etc.)  
- **Target**:  
  - `0` → Healthy  
  - `1` → Diseased  

---

## ⚙️ What I Implemented
- Data preprocessing (scaling & splitting).  
- **Exploratory Data Analysis (EDA)**: distributions, correlation heatmap.  
- Trained Logistic Regression model with feature scaling.  
- Evaluated using:
  - Accuracy, Precision, Recall, F1-score  
  - Confusion Matrix  
  - ROC–AUC Curve  
- **Cross-validation** for stability check.  
- Compared Logistic Regression with **Random Forest** & **SVM**.  
- Created a **user input prediction function**.  

---

## 📈 Results
- Logistic Regression achieved strong classification performance.  
- ROC–AUC Curve shows good separation between classes.  
- Feature importance highlights key medical factors influencing predictions.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/heart-disease-prediction.git
   cd heart-disease-prediction
