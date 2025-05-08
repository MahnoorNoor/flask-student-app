### 📚 Flask Student Management App
This is a simple web application built using Flask and SQLite that performs basic CRUD operations for managing student records.

### 🚀 Features
Add new students

View all student records

Update student information

Delete student records

### 🛠️ Technologies Used:
Python

Flask

Flask SQLAlchemy

SQLite

HTML (Jinja2 templates)

### 📂 Project Structure

FlaskApp/
│
├── app.py                   # Main Flask app
├── templates/
│   ├── index.html           # Main page for displaying and adding students
│   └── update.html          # Page to update student data
├── .venv/                   # Python virtual environment
└── firstapp.db              # SQLite database (auto-generated)
### ⚙️ Setup Instructions
### Clone the repository:

git clone https://github.com/your-username/FlaskApp.git
cd FlaskApp

### Set up a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

### Install dependencies:
pip install flask flask_sqlalchemy

### Run the application:
python app.py

### Visit the app in your browser:

http://127.0.0.1:5000/
