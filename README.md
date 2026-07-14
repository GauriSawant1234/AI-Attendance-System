# 🎓 AI Attendance System

An AI-powered attendance management system built with **Python**, **Streamlit**, and **Supabase** that uses **face recognition** and **voice recognition** to simplify classroom attendance.

---

## 📌 Overview

The AI Attendance System provides an intelligent way to manage classroom attendance by allowing teachers to create subjects, enroll students, and mark attendance using biometric features such as face and voice recognition.

The application provides separate interfaces for teachers and students and stores all attendance data securely in Supabase.

---

## ✨ Features

### 👨‍🏫 Teacher Module
- Teacher Registration & Login
- Secure password hashing using bcrypt
- Create and manage subjects
- View enrolled students
- Track attendance history
- Attendance analytics

### 👨‍🎓 Student Module
- Student registration
- Face enrollment
- Voice enrollment
- Subject enrollment
- View attendance records
- Automatic attendance support

### 🤖 AI Features
- Face Recognition
- Voice Recognition
- Face Embedding Generation
- Voice Embedding Generation
- Automatic Student Recognition

### ☁️ Database
- Cloud database using Supabase
- Student management
- Teacher management
- Subject management
- Attendance logs

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3.11 | Backend |
| Streamlit | Web Application |
| Supabase | Database |
| PostgreSQL | Data Storage |
| bcrypt | Password Encryption |
| OpenCV | Image Processing |
| Face Recognition | Facial Authentication |
| Speech Recognition | Voice Recognition |

---

## 📂 Project Structure

```
AI-Attendance-System/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── src/
│   ├── components/
│   ├── database/
│   ├── pipelines/
│   ├── screens/
│   └── ui/
│
└── .streamlit/
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/GauriSawant1234/AI-Attendance-System.git

cd AI-Attendance-System
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure Supabase

Create a file named

```
.streamlit/secrets.toml
```

Add:

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"
SUPABASE_KEY="YOUR_SUPABASE_ANON_KEY"
```

> Do **not** commit your `secrets.toml` file to GitHub.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Teacher Dashboard
- Student Dashboard
- Subject Management
- Attendance Screen
- Face Enrollment
- Voice Enrollment

---

## 🚀 Future Improvements

- Real-time webcam attendance
- Multi-face recognition
- Attendance reports in PDF
- Email notifications
- Mobile application
- QR code attendance
- Dashboard analytics
- Face liveness detection

---

## 📚 Skills Demonstrated

- Python Programming
- Streamlit Development
- Database Integration
- PostgreSQL
- Supabase
- Password Hashing
- AI-based Authentication
- Face Recognition
- Voice Recognition
- Software Architecture

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a Pull Request

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👤 Author

**Gauri Sawant**

GitHub: https://github.com/GauriSawant1234

---

⭐ If you found this project helpful, consider giving it a star!
