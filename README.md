# 🎓 Flask Student Management App

This is a simple web application built with **Flask** that allows users to **add, view, update, and delete student records**. It uses **SQLite** as a backend database and **SQLAlchemy** as the ORM.

---

## 📋 Features

- ✅ Add new student records (First Name, Last Name, Age, City)
- 🧾 View a list of all students
- 🔁 Update existing student information
- ❌ Delete a student record

---

## 🛠 Technologies Used

- **Python**
- **Flask** – Lightweight web framework
- **Flask-SQLAlchemy** – ORM for interacting with SQLite
- **HTML + Jinja2** – For frontend templates

---

## 📁 Project Structure

FlaskStudentApp/
├── app.py # Main Flask application
├── templates/
│ ├── index.html # Homepage with add form & student table
│ └── update.html # Form to update student record
├── requirements.txt # Project dependencies
└── .gitignore # Files and folders to ignore in Git

## ▶️ Getting Started

### 1. Clone the Repository


git clone https://github.com/yourusername/flask-student-app.git
cd flask-student-app

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Run the App

python app.py

The app will be available at:
👉 http://127.0.0.1:5000/
