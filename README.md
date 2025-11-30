# Heart-Disease-Prediction-Using-Machine-Learning
The goal of this project was to build a machine learning–based assistant that can estimate the likelihood of heart disease from patient data and provide lifestyle-oriented recommendations based on the predicted risk.
# 🫀 Heart Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)


A machine learning-based assistant that predicts the likelihood of heart disease from patient clinical data and provides personalized, risk-based lifestyle recommendations. This project demonstrates a complete ML pipeline from data exploration to model deployment-ready code.

---

## 📖 Project Overview

Cardiovascular diseases are the leading cause of death globally. This project aims to serve as an **educational and screening-support tool** that uses machine learning to identify individuals at high risk, encouraging them to seek professional medical advice.

**Key Features:**
- **Risk Prediction:** Estimates the probability of heart disease based on 13 clinical features.
- **Intelligent Recommendations:** Provides tailored lifestyle and medical advice based on a 5-level risk system.
- **Model Comparison:** Implements and evaluates four different ML algorithms to find the most effective one.
- **Ethical by Design:** Emphasizes that the tool is for guidance only and not a replacement for a medical diagnosis.

---

## 📊 Dataset

We used the **UCI Heart Disease Dataset**, a widely-used benchmark in medical ML.

- **Source:** https://archive.ics.uci.edu/ml/datasets/Heart+Disease
- **Samples:** 1,025  
- **Features:** 13 clinical attributes (age, sex, chest pain type, resting blood pressure, cholesterol levels, maximum heart rate, etc.)  
- **Target:** Binary (0 = No Disease, 1 = Heart Disease)

---

## 🛠️ Installation & Usage

### Prerequisites
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```
### Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. **Open the .ipynb script:**

## 🧠 ML Pipeline & Methodology

### 1. Data Preprocessing
- Checked for missing values  
- Stratified 80/20 train-test split  
- Applied StandardScaler  

### 2. Models Implemented
- Gaussian Naive Bayes  
- Decision Tree Classifier  
- Random Forest Classifier  
- Logistic Regression  

### 3. Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  


---

## 📈 Results

| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| ------------------- | :------: | :-------: | :----: | :------: | :-----: |
| Naive Bayes         |  0.8293  |  0.8070   | 0.8762 |  0.8402  | 0.9043  |
| Decision Tree       |  0.8390  |  0.8214   | 0.8762 |  0.8479  | 0.8957  |
| **Random Forest**   | **0.9659** | **0.9623** | **0.9714** | **0.9668** | **0.9880** |
| Logistic Regression |  0.8098  |  0.7619   | 0.9143 |  0.8312  | 0.9298  |


---

## 💡 Recommendation System

| Risk Level       | Probability Range | Recommendation |
| ---------------- | ----------------- | -------------- |
| 🟢 **Very Low**  | 0.00 – 0.20       | Maintain a healthy lifestyle and routine check-ups. |
| 🟡 **Low**       | 0.20 – 0.40       | Continue healthy habits and monitor key metrics. |
| 🟠 **Moderate**  | 0.40 – 0.60       | Recommended to have a proper medical check-up. |
| 🔴 **High**      | 0.60 – 0.80       | Strongly advised to consult a cardiologist soon. |
| 🚨 **Very High** | 0.80 – 1.00       | Urgently recommend immediate medical evaluation. |


---

## ⚠️ Ethical Considerations & Limitations

- Not a diagnostic tool  
- Dataset may not generalize to all populations  
- Limited feature set (13 features)  
- Possible false positives & false negatives  


---

## 👨‍💻 Authors

- **Ali Shah** — https://github.com/4LIshah  
- **Hassam-Ur-Rehman** — https://github.com/

**Class:** BS AI 
**Institution:** Bahria University, Islamabad  
