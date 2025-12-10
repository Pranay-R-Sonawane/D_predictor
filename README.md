# 🩺 Diabetes Prediction App (Machine Learning + Streamlit)

A clean and interactive **Machine Learning web application** built with **Streamlit** that predicts whether a user is likely to have **Diabetes** based on key medical and lifestyle inputs.  
Fast, simple, and built to help users understand their health better.

🔗 **Live App:** https://dpredictor.streamlit.app/

---

## 🚀 Overview

This project uses a trained ML model on the **Sample Take It From Chatgpt** to make predictions in real-time.  
Users enter basic health information — such as BMI, Glucose, Blood Pressure, Insulin levels, and lifestyle habits — and the app instantly returns the result.

The goal: **Accessible health prediction through data and clean UI.**

---

## 🧠 How It Works

- The dataset is cleaned and preprocessed  
- A Machine Learning model is trained  
- The model is saved using `pickle`  
- Streamlit loads the model & predicts based on user inputs  
- The app provides a simple, easy-to-understand result  

---

## 🛠️ Tech Stack

| Area | Technology |
|------|------------|
| Frontend | Streamlit |
| Backend | Python |
| ML Model | Scikit-Learn |
| Data | Sample Dataset From Chatgpt|
| Deployment | Streamlit Cloud |

---

## 📥 Installation & Usage

Clone the project and run it locally:

```bash
git clone <your-repo-link>
cd <your-repo-folder>
pip install -r requirements.txt
streamlit run app.py   # or your main file name
