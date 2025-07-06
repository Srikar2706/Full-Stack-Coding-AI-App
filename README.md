# 🧠 AI-Powered Coding Challenge Generator

This is a full-stack web application that uses **OpenAI's GPT models** to generate **multiple-choice coding challenges** on demand. Built with **FastAPI** (Python) for the backend and **React** (JavaScript) for the frontend, it includes secure authentication via **Clerk** and a **history tab** where users can view all previously generated challenges.


<p align="center">
  <img src="https://img.shields.io/badge/Backend-FastAPI-green.svg" />
  <img src="https://img.shields.io/badge/Frontend-React-blue.svg" />
  <img src="https://img.shields.io/badge/Auth-Clerk-purple.svg" />
  <img src="https://img.shields.io/badge/AI-OpenAI GPT-red.svg" />
</p>

---

## 🧩 Features

- ✅ Generate **custom multiple-choice coding questions**
- 📚 View and revisit all your previous questions in a **History tab**
- 🔐 Secure login & registration with **Clerk Authentication**
- 🧠 **OpenAI GPT Integration** to produce high-quality, unique challenges
- 💾 **Persistent challenge history** using a **SQLite** database
- ⚡ Built with modern full-stack tech: **FastAPI + React + Vite**

---

## 🔧 Tech Stack

| Layer        | Technology            |
|--------------|------------------------|
| Frontend     | React, Vite, JavaScript |
| Backend      | FastAPI, Python         |
| Authentication | Clerk                  |
| AI           | OpenAI GPT    |
| Database     | SQLite    |

---



## Usage

### 1. Clone the repository

```bash
git clone https://github.com/Srikar2706/Full-Stack-Coding-AI-App.git
cd ai-coding-challenges
```

### 2. Run Frontend
```bash
cd frontend
npm start
```


### 3. Run Backend
```bash
cd backend
uvicorn main:app --reload
```



