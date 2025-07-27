# ISMS – Fullstack Institute/Integrated Student Management System

## 📌 Overview

This repository hosts the **fullstack implementation** of the Institute/Integrated Student Management System (**ISMS**), built to streamline academic and administrative operations.

---

## 🔧 Tech Stack

### Backend
- Java 17
- Spring Boot
- Gradle
- Firebase (Authentication and Notifications)
- Google Groups (Group Emails)
- Docker

### Frontend
- HTML5
- CSS3
- SVG/PNG/JPG Assets

---

## 🚀 Features

### Backend
- RESTful APIs for:
  - Students
  - Faculty
  - Courses
  - Grievances
  - Notices
  - Results
- Firebase Authentication & Authorization
- Google Group integration for bulk emails
- Modular structure for scalability
- Docker-ready for containerized deployment

### Frontend
- Role-Based Dashboards:
  - Student
  - Faculty
  - Director
  - Exam Cell
  - Librarian
- Academic features: Grades, Courses, Timetable
- Administrative: Fees, Grievances, Notices
- Library Management
- Responsive UI with clean layout

---

## 📁 Folder Structure

### Backend
```
backend/
├── controller/      # REST Controllers
├── service/         # Business Logic
├── model/           # Data Models
├── config/          # Spring Configuration
└── resources/       # Application Properties, Firebase Credentials
```

### Frontend
```
frontend/
├── index.html        # Login Page
├── s_*.html/css      # Student Pages
├── f_*.html/css      # Faculty Pages
├── d_*.html/css      # Director Pages
├── e_*.html/css      # Exam Cell Pages
├── l_*.html/css      # Librarian Pages
└── assets/           # Images (SVG/PNG/JPG)
```

---

## ⚙️ Getting Started

### Backend Setup

1. **Clone the repository**
2. **Configure Firebase and Google credentials** inside `src/main/resources`
3. **Build the project**  
   ```bash
   ./gradlew build
   ```
4. **Run the application**  
   ```bash
   ./gradlew bootRun
   ```
5. Access the APIs at:  
   ```
   http://localhost:8080/
   ```

### Frontend Setup

1. Open the required `.html` file in a web browser  
   - Example: `index.html` for login  
   - `s_home.html` for student dashboard, etc.

---

## 🤝 Contribution

- Contributions are welcome!
- Fork the repo and submit a pull request
- For major changes, please open an issue first to discuss what you’d like to change

---

## 📜 License

[Specify your license here]
