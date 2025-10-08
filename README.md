# 🌾 Agriculture Chatbot (Task 2)

## 📘 Overview
An AI-powered **Agriculture Chatbot** built using **Flask** with **user authentication**.  
Users can **register**, **log in**, and chat with a virtual farming assistant that provides advice on **fertilizers**, **pests**, and **weather**.

---

## 🗂️ Project Structure

📁 Agriculture Chatbot
│
├── app.py # Main Flask app with routes & authentication
├── chatbot_model.py # Chatbot logic & responses
│
├── templates/
│ ├── login.html # Login page
│ ├── register.html # Registration page
│ └── index.html # Chat interface
│
├── static/
│ └── style.css # CSS styling
│
└── database.db # SQLite database (auto-created)


---

## ⚙️ Setup Instructions

### 1️⃣ Install Dependencies

pip install flask flask_sqlalchemy flask_bcrypt

### 2️⃣ Run the App

python app.py

###3️⃣ Open in Browser

👉 http://127.0.0.1:5000/

💬 Chatbot Features

Responds to queries on fertilizer, pests, and weather

Provides general agriculture tips

Simple & clean chat UI

🔐 Authentication Features

Secure user registration & login

Passwords hashed with Flask-Bcrypt

Session management with Flask-Session

🧰 Tech Stack

Python (Flask Framework)

HTML, CSS, JavaScript

SQLite Database


