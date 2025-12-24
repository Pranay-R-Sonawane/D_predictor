# 🩺 Diabetes Prediction App

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white) 
![Streamlit](https://img.shields.io/badge/Streamlit-1.30-orange?logo=streamlit&logoColor=white) 
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranay-sonawane/) 
[![Portfolio](https://img.shields.io/badge/Portfolio-View-lightgrey?logo=google-chrome&logoColor=white)](https://your-portfolio-link.com)

A clean and interactive **Machine Learning web application** built with **Streamlit** to predict whether a user is likely to have **Diabetes** based on key medical and lifestyle inputs.

🔗 **Live App:** https://dpredictor.streamlit.app/

---

## 📑 Table of Contents
- [Introduction](#✨-introduction)
- [Overview](#🚀-overview)
- [Advantages of Early Detection](#🌟-advantages-of-early-detection-who)
- [Disadvantages of Late Detection](#⚠️-disadvantages-of-late-detection)
- [Why I Built This App](#🎯-why-i-built-this-app)
- [How It Works](#🧠-how-it-works)
- [Tech Stack](#🛠️-tech-stack)
- [Tools & IDEs](#🧰-tools--ides)
- [Sample Screenshot](#🖼️-sample-screenshot)
- [Installation & Usage](#📥-installation--usage)
- [Future Improvements](#🚧-future-improvements)
- [Skills Highlight](#💡-skills-highlight)

---

## ✨ Introduction
This app analyzes health parameters like **Glucose**, **BMI**, **Blood Pressure**, and **Insulin** to predict diabetes risk.  
The goal: **Fast, accurate, accessible health prediction through a modern UI.**

---

## 🚀 Overview
- Trained ML model on a sample dataset  
- Real-time predictions using Streamlit  
- Clean and responsive UI  
- Lightweight and beginner-friendly  

---

## 🌟 Advantages of Early Detection (WHO)
### 🎯 1. Slows Disease Progression  
Early treatment helps prevent long-term organ damage.

### ❤️ 2. Reduces Serious Complications  
Prevents heart attacks, strokes, kidney failure, blindness, and nerve damage.

### 🧠 3. Better Quality of Life  
People diagnosed early stay healthier and more productive.

### 💊 4. Simple Tests Work Best Early  
Basic tests like fasting glucose or HbA1c detect diabetes at the right time.

### 💰 5. Cuts Long-Term Costs  
Treating advanced diabetes is expensive — early care is far cheaper.

### 📊 6. Prevents Related Health Issues  
Helps detect eye, kidney, and cardiovascular problems early.

👉 **Early detection saves lives and prevents disability.**

---

## ⚠️ Disadvantages of Late Detection
- Chronic fatigue, blurred vision, weight loss  
- Heart, kidney, nerve, and eye damage  
- Higher risk of stroke, ulcers, and amputations  
- Higher medical costs and reduced quality of life  

---

## 🎯 Why I Built This App
According to WHO:  
- Diabetes cases grew from **200M (1990)** → **830M (2022)**  
- Over **50%** of patients didn't receive medication in 2022  
- Causes blindness, kidney failure, heart disease, stroke  
- Led to **2M+ deaths in 2021**  
- 11% of cardiovascular deaths come from high blood glucose  

This app helps users quickly check their risk and encourages early screening.

---

## 🧠 How It Works
- Clean dataset  
- ML model trained using Scikit-Learn  
- Model saved with `pickle`  
- Streamlit predicts in real-time  
- User inputs → model outputs result instantly  

---

## 🛠️ Tech Stack
| Area | Technology |
|------|------------|
| Frontend | Streamlit |
| Backend | Python |
| ML Model | Scikit-Learn |
| Data | Sample Dataset |
| Deployment | Streamlit Cloud |

---

## 🧰 Tools & IDEs
**IDEs:** Google Colab, PyCharm  
**Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Streamlit, Time, Joblib, Imblearn

---

## 🖼️ Sample Screenshot
![App Screenshot](https://raw.githubusercontent.com/PranaySonawane-dataanalyst/D_predictor/main/Sample%20Screenshot.png)

---

## 📥 Installation & Usage
```bash
git clone https://github.com/PranaySonawane-dataanalyst/D_predictor.git
cd D_predictor
pip install -r requirements.txt
streamlit run D_predictor.py   # or your main file
