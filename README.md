# 📖 Digital Diary

> A secure, AI-powered digital journaling application built using React, FastAPI, and PostgreSQL.

![React](https://img.shields.io/badge/React-19-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange)
![Render](https://img.shields.io/badge/Deployment-Render-purple)

---

## 🌐 Live Demo
- Frontend: https://digital-diary-frontend.onrender.com
- Backend: https://digital-diary-backend-0n51.onrender.com

> **Note:** Hosted on Render's free tier — the first load may take ~30-60 seconds to spin up.

---

## 📂 Source Code
- Frontend Repository: https://github.com/PallatiTejasree/Digital-diary-frontend
- Backend Repository: https://github.com/PallatiTejasree/Digital-diary-backend

---

## 📌 Project Overview
Digital Diary is a full-stack web application that allows users to securely write, manage, and reflect on their personal memories. It provides JWT-based authentication, full CRUD diary management, AI-powered reflections, and cloud deployment, making it accessible from any device.

---

## ✨ Features
- Secure login using JWT authentication
- Create, edit, and delete diary entries
- Timeline view of past memories
- Archive memories
- AI-powered reflection generation
- Profile page
- Responsive, mobile-friendly UI
- Cloud-hosted and accessible from any device

---

## 🛠 Tech Stack

**Frontend**
- React
- React Router
- CSS3
- JavaScript

**Backend**
- FastAPI
- SQLAlchemy
- JWT Authentication
- Passlib
- Python

**Database**
- PostgreSQL

**Deployment**
- Render

**Version Control**
- Git, GitHub

---

## 🏗 System Architecture
```
React Frontend
      │
      │  REST API
      ▼
FastAPI Backend
      │
      │  SQLAlchemy ORM
      ▼
PostgreSQL Database
```

---

## 📁 Project Structure
```
Digital Diary
├── Frontend (React)
├── Backend (FastAPI)
└── PostgreSQL Database
```

---

## 🔒 Authentication
The application uses JWT authentication for secure user sessions.
- Login API
- Protected routes
- Token verification
- Secure user sessions

---

## 📚 APIs

**User**
- `POST /signup`
- `POST /login`
- `GET /me`

**Diary**
- `GET /diary`
- `POST /diary`
- `PUT /diary/{id}`
- `DELETE /diary/{id}`

**Reflection**
- `POST /reflection`

---

## 🚀 Deployment
- Frontend — Render Static Site
- Backend — Render Web Service
- Database — PostgreSQL

---

## 🎯 Future Enhancements
- Password reset
- Email verification
- Mood analytics
- Calendar view
- Image uploads
- Voice notes
- PWA support
- Dark mode

---

## 👩‍💻 Author
**Tejasree Pallati**
Electronics and Communication Engineering Graduate, CBIT Hyderabad

- GitHub: https://github.com/PallatiTejasree
- LinkedIn: https://www.linkedin.com/in/tejasree-pallati-71465b301/

---
---

## 📸 Application Screenshots

### 🌟 Splash Screen

![Splash Screen](Frontend/Images/Splash-Screen.png)

---

### 🔐 Login Page

![Login Page](Frontend/Images/Login-Page.png)

---

### 🏠 Home Page

![Home Page](Frontend/Images/Home-Page.png)

---

### 📊 Editor Dashboard

![Editor Dashboard](Frontend/Images/Editor-Dashboard.png)

---

### ✍️ Editor Main Page

![Editor Main Page](Frontend/Images/Editor-Main-Page.png)

---

### 🌸 Reflection Dashboard

![Reflection Dashboard](Frontend/Images/Reflection-Dashboard.png)

---

### 📈 Mood Analytics

![Mood Analytics](Frontend/Images/Mood-Analytics.png)

---

### 🤖 AI Insights

![AI Insights](Frontend/Images/AI-Insights.png)

---
⭐ If you like this project, consider giving it a star.
