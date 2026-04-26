# 🎯 AI-Driven Career Counseling System

## 📌 Overview

The AI-Driven Career Counseling System is a full-stack machine learning project that helps students choose the right career path based on their interests, skills, and academic performance.

It uses a trained ML model to generate personalized career recommendations and stores user data in a MySQL database.

---

## 🚀 Features

* 🧠 AI-based Career Recommendation
* 📊 Student Profiling (Interest, Skills, Marks)
* 💾 MySQL Database Integration
* ⚡ FastAPI Backend (High performance API)
* 🎨 Streamlit Frontend (Interactive UI)
* 📈 Scalable and modular architecture

---

## 🛠️ Tech Stack

| Layer    | Technology   |
| -------- | ------------ |
| Frontend | Streamlit    |
| Backend  | FastAPI      |
| ML Model | Scikit-learn |
| Database | MySQL        |
| Language | Python       |

---

## 🧩 Project Structure

career-ai-system/
│── app/
│   │── main.py
│   │── model.py
│   │── predict.py
│   │── database.py
│   │── schemas.py
│
│── frontend/
│   │── app.py
│
│── data/
│   │── career_data.csv
│
│── models/
│   │── model.pkl
│
│── requirements.txt
│── README.md

---
---

## 📊 How It Works

1. User enters details (interest, skills, marks)
2. Data is sent to FastAPI backend
3. ML model predicts career
4. Result is stored in MySQL
5. Recommendation is shown on UI
