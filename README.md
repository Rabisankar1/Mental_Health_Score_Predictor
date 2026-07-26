# 🧠 Mental Health Score Predictor

<p align="center">

<img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn" />
<img src="https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge&logo=fastapi" />
<img src="https://img.shields.io/badge/Frontend-HTML%20CSS%20JavaScript-blue?style=for-the-badge&logo=javascript" />
<img src="https://img.shields.io/badge/Deployment-Render-46E3B7?style=for-the-badge&logo=render" />
<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

</p>

<p align="center">

### 🎯 Predict Student Mental Health Score Using Machine Learning

A modern **Machine Learning + FastAPI** web application that predicts a student's **Mental Health Score (0–10)** based on social media usage, academic performance, lifestyle habits, and stress level.

🌐 **Live Demo:**  
👉 **https://mental-health-score-predictor-2.onrender.com/**

</p>

---

# 📖 Overview

The **Mental Health Score Predictor** is an end-to-end Machine Learning application that estimates a student's mental well-being using various behavioral and lifestyle factors.

This project demonstrates the complete deployment pipeline of an ML model—from data preprocessing and model training to API development and frontend integration.

---

# ✨ Key Features

✅ Predict Mental Health Score (0–10)

✅ Beautiful Responsive User Interface

✅ FastAPI REST API

✅ Machine Learning Prediction

✅ Input Validation with Pydantic

✅ Multiple Country Support

✅ Real-Time Predictions

✅ Render Cloud Deployment

✅ Clean UI & Fast Performance

---

# 🖥 Live Website

### 🌐 https://mental-health-score-predictor-2.onrender.com/

---

# 🚀 Technology Stack

## 🎨 Frontend

- HTML5
- CSS3
- JavaScript (ES6)

---

## ⚙ Backend

- FastAPI
- Pydantic
- Uvicorn

---

## 🤖 Machine Learning

- Scikit-Learn
- Pandas
- Joblib

---

## ☁ Deployment

- Render

---

# 📂 Project Structure

```text
Mental-Health-Score-Predictor/
│
├── main.py
├── Mental_Health_Model.pkl
├── requirements.txt
├── README.md
│
├── index.html
├── style.css
├── script.js
│
└── Mental_Health_Score_Predictor.ipynb
```

---

# 📊 Input Features

The prediction model uses the following features:

| Feature | Description |
|----------|-------------|
| 👤 Age | Student Age |
| 🚻 Gender | Male / Female |
| 🌍 Country | Student Country |
| 🎓 Academic Level | Undergraduate / Graduate |
| 📱 Most Used Platform | Instagram, Facebook, etc. |
| 🎯 Purpose of Use | Education / Entertainment |
| ⏰ Daily Usage Hours | Average Social Media Usage |
| 🔓 Daily Unlocks | Phone Unlock Count |
| 📚 Study Hours | Daily Study Time |
| 🏃 Physical Activity | Exercise Hours |
| 😴 Sleep Hours | Average Sleep |
| 😰 Stress Level | Low / Medium / High |

---

# 🔄 How It Works

```text
User Input
      │
      ▼
Frontend (HTML/CSS/JS)
      │
      ▼
FastAPI REST API
      │
      ▼
Machine Learning Model
      │
      ▼
Mental Health Score Prediction
      │
      ▼
Displayed on Website
```

---

# 🔗 REST API

## Predict Mental Health Score

### Endpoint

```http
POST /predict
```

### Request

```json
{
  "age": 21,
  "gender": "Male",
  "country": "India",
  "academic_level": "Undergraduate",
  "most_used_platform": "Instagram",
  "purpose_of_use": "Education",
  "avg_daily_usage_hours": 4.5,
  "daily_unlocks": 80,
  "study_hours": 5,
  "physical_activity_hours": 1,
  "sleep_hours_per_night": 7,
  "stress_level": "Medium"
}
```

---

### Response

```json
{
    "predicted_mental_health_score": 7.42
}
```

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/Rabisankar1/Mental-Health-Score-Predictor.git
```

Move into the project

```bash
cd Mental-Health-Score-Predictor
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run FastAPI

```bash
uvicorn main:app --reload
```

Open

```
http://127.0.0.1:8000
```

---

# 📸 Application Screenshot

## Prediction Result

<img width="900" alt="Prediction" src="https://github.com/user-attachments/assets/fac43b28-3171-4e54-9e83-e8fb0a929b55">

---

# 🚀 Future Enhancements

- 🔐 User Authentication
- 📈 Dashboard Analytics
- 📊 Prediction History
- 📉 Interactive Charts
- 🌙 Dark Mode
- 📄 PDF Report Download
- 🐳 Docker Support
- ☁ CI/CD Pipeline
- 📱 Progressive Web App (PWA)

---

# 💡 Learning Outcomes

This project demonstrates practical experience in:

- Machine Learning Model Deployment
- REST API Development
- FastAPI
- Pydantic Validation
- Frontend–Backend Integration
- Responsive Web Design
- Cloud Deployment with Render
- Git & GitHub Workflow

---

# 👨‍💻 Author

## **Rabisankar Pradhan**

🎓 B.Tech CSE (Data Science)

🔗 **GitHub**

https://github.com/Rabisankar1

💼 **LinkedIn**

https://www.linkedin.com/in/rabisankar-pradhan-362986313/

---

# 🌟 Show Your Support

If you found this project useful,

⭐ **Star this repository**

🍴 **Fork this repository**

📢 **Share it with others**

---

<p align="center">

### ❤️ Thanks for visiting my project!

Made with ❤️ using **FastAPI + Scikit-Learn + JavaScript**

</p>
