# SchoolOS-Student-Teacher-Management-System




# 🏫 SchoolOS - Smart School Management System

A modern School Management System built using **Python**, **OOP Concepts**, **JSON Database**, and **Streamlit**. The application helps manage students, teachers, and academic records through an interactive dashboard.

---

## 🚀 Features

### 👨‍🎓 Student Management
- Register new students
- Store student information
- Validate email addresses
- Prevent duplicate roll numbers
- View student details
- Calculate average grades

### 👨‍🏫 Teacher Management
- Register teachers
- Store subject information
- Prevent duplicate employee IDs
- View teacher details

### 📊 Grade Management
- Add subject-wise grades
- Track student performance
- Calculate average marks
- Maintain academic records

### 📈 Dashboard Analytics
- Total Students
- Total Teachers
- Grades Recorded
- School Average Performance
- Recent Students Overview
- Faculty Overview

### 💾 Data Storage
- JSON-based database
- Automatic data saving
- Persistent records

---

## 🛠️ Technologies Used

- Python 3
- Streamlit
- Object-Oriented Programming (OOP)
- JSON
- Abstract Base Classes (ABC)
- Pathlib

---

## 📂 Project Structure

```text
SchoolOS/
│
├── app.py                # Streamlit Web Application
├── main.py               # Console Version
├── school_data.json      # Database File
├── README.md
│
└── assets/
```

---

## 🏗️ OOP Concepts Implemented

### Abstraction
Implemented using Abstract Base Classes (ABC).

### Inheritance
Student and Teacher classes inherit from the Person abstract class.

### Polymorphism
Different implementations of common methods.

### Encapsulation
Data handled through class methods and controlled access.

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/SchoolOS.git
cd SchoolOS
```

### Install Dependencies

```bash
pip install streamlit
```

### Run Application

```bash
streamlit run app.py
```

---

## 📸 Screens

### Dashboard
- Student Statistics
- Teacher Statistics
- School Average

### Student Module
- Student Registration
- Student Details
- Grade Tracking

### Teacher Module
- Teacher Registration
- Teacher Details

---

## 📋 Sample Data

### Student

```json
{
  "name": "Rahul",
  "age": 21,
  "email": "rahul@gmail.com",
  "roll_no": "1",
  "grades": {
    "Maths": 90
  }
}
```

### Teacher

```json
{
  "name": "Prajwal",
  "age": 45,
  "email": "prajwal@gmail.com",
  "subject": "Maths",
  "emp_id": "1"
}
```

---

## 🎯 Learning Outcomes

- Python Programming
- Object-Oriented Programming
- Streamlit Development
- File Handling
- JSON Data Management
- Data Validation
- Dashboard Design

---

## 🌟 Future Enhancements

- Login Authentication
- Attendance Management
- AI Performance Prediction
- PDF Report Generation
- Database Integration (MySQL)
- Email Notifications
- Student Search Feature
- Data Visualization Charts

---

## 👨‍💻 Author

**Rahul Gunjal**

- Python Developer
- Software Development Enthusiast

---

## ⭐ Support

If you like this project:

⭐ Star the repository

🍴 Fork the repository

📢 Share with others

---

Made with ❤️ using Python & Streamlit
