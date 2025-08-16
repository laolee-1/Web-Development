# 📚 E-Learning Web Platform

Hi there! 👋 This project is a full-stack web application I built as part of my Advanced Web Development coursework. It's designed to simulate a real-world e-learning system with two types of users: **teachers** and **students** also includes key features like course creation, content sharing, and real-time chat.

## ✨ What It Does

- 🔐 **Login System** for both students and teachers  
- 📘 **Teachers** can create, manage, and publish courses  
- 🧑‍🎓 **Students** can view and enroll in available courses  
- 💬 **Live Chat** between students and teachers using WebSockets  
- 🗂️ **File and Content Upload** for lessons or assignments  
- 🧾 **User Profiles** for better personalization  

This project is a hands-on demonstration of how web technologies come together to deliver interactive, user-focused experiences.

---

## 🛠️ Built With

### Frontend (React)
- ReactJS (for building UI)
- Axios (for handling API requests)
- WebSocket support for real-time chat

### Backend (Django)
- Django & Django REST Framework
- SQLite database (easily switchable to PostgreSQL)
- Token-based authentication

---

## 🚀 How to Run It Locally

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
