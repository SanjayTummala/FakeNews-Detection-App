# 📰 Fake News Detection – Full Stack Web Application

A complete Machine Learning–powered web application that identifies whether a news statement is Fake or Real.  
This project integrates a trained ML model, a Flask-based backend API, and a modern React frontend, deployed on cloud platforms for seamless real-time predictions.


---

## 🟦 Frontend README – `Fakenews-Detection-frontend`

# 🌐 Fake News Detection – Frontend (React)

This repository contains the **React-based frontend** for the Fake News Detection project.  
It provides a modern, tab-based UI where users can paste news text and see whether it is predicted as **fake** or **real** by the backend ML API.

---

## 📌 Overview

- ⚛️ **Frontend Framework:** React.js
- 🎨 **UI:** Custom CSS (single-page app)
- 🌐 **Backend:** Flask ML API (Render)
- ☁️ **Deployment:** Vercel
- 🧠 **Use Case:** Simple, educational UI for demonstrating fake news detection

---

## 🌍 Live Demo

> **Deployed Frontend:**  
> `https://fakenews-detection-frontend.vercel.app/`

> **Backend API (used by this app):**  
> `https://fakenews-detection-backend.onrender.com`

---

## ✨ Features

- 🔍 **Detector Tab**
  - Paste any news statement / headline / short article
  - Click **“Detect Fake News”**
  - Displays result as **Fake News** or **Real News** with color-coded cards
  - Shows helpful note about verifying from trusted sources

- 📘 **About Tab**
  - Explains the project goal and how ML + NLP are used
  - Simple explanation of TF-IDF and Naive Bayes for non-technical viewers

- 📊 **Dataset & Samples Tab**
  - Describes the combined dataset (~54k+ labeled samples)
  - Briefly explains preprocessing and training
  - Includes **5 sample fake news examples** and **5 sample real news examples** for demonstration

- 🛠 **Tech & Architecture Tab**
  - Breaks down the full stack:
    - Frontend (React)
    - Backend API (Flask)
    - ML & NLP (TF-IDF + Naive Bayes)
    - Architecture diagram (User → React → Flask → Model)
  - Very useful for **faculty, recruiters, and reviewers**

---

## 🧱 Tech Stack

**Frontend:**
- React.js
- JavaScript (ES6+)
- HTML5, CSS3
- Fetch API

**Backend (external service):**
- Flask (Python)
- Scikit-learn
- TF-IDF vectorizer
- Multinomial Naive Bayes
- Deployed on Render

**Deployment:**
- Vercel (for React app)
- Environment variable `REACT_APP_API_URL` for backend base URL

---

## 🗂 Project Structure

```bash
frontend/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── App.js          # Main UI with tabs, detector, info sections
│   ├── App.css         # Styling (modern card + tab-based layout)
│   ├── index.js        # React entry point
│   └── ...
│
├── package.json
└── README.md

```

## 📁 Repositories

Frontend  
https://github.com/SanjayTummala/Fakenews-Detection-frontend

Backend  
https://github.com/SanjayTummala/Fakenews-Detection-backend

Main Documentation (this repo)  
https://github.com/SanjayTummala/FakeNews-Detection-App

---

## 🖼️ Screenshots

All screenshots, demo previews, and architecture diagrams will be stored inside the `assets/` folder of this repository for clean documentation.

---

## 👨‍💻 Author

**Sanjay Kumar Tummala**  
Machine Learning • Networking • Web Application Development
