# 🏥 Hospital Management System

## 📌 Overview
The **Hospital Management System** is a full-stack application designed to streamline hospital operations, including patient management, doctor appointments, authentication, and more. The system is divided into **frontend** (React) and **backend** (Django) components, ensuring scalability and modularity.

## 🚀 Features
- **User Authentication** (Signup/Login)
- **Doctor & Patient Management**
- **Appointment Booking System**
- **Admin Dashboard** for managing records
- **Database-Driven** system with migrations and seed data
- **RESTful API** for smooth frontend-backend communication
- **CI/CD Integration** using GitHub Actions

## 🏗️ Tech Stack
### **Frontend (React.js)**
- React.js
- Redux
- Tailwind CSS
- Axios
- React Router

### **Backend (Django & Django REST Framework)**
- Django
- Django REST Framework
- PostgreSQL
- Docker
- Gunicorn

## 📂 Project Structure
```
/hospital-management-system
│── frontend/              # React.js frontend
│── backend/               # Django backend
│── database/              # Database migrations & seed data
│── tests/                 # Unit & integration tests
│── docs/                  # Documentation
│── scripts/               # Deployment scripts
└── .github/workflows/     # CI/CD configuration
```

## 🔧 Installation
### **Prerequisites:**
- Node.js & npm (for frontend)
- Python 3 & pip (for backend)
- PostgreSQL (or SQLite for local development)
- Docker (for containerized deployment)

### **Setup Backend**
```bash
cd backend
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### **Setup Frontend**
```bash
cd frontend
npm install
npm start
```

## 🏛️ Database Schema & Diagrams
### **📌 ER Diagram**
*ERdiagram.png*

### **📌 UML Diagram**
*DBschema.png*

## 📜 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| `POST` | `/auth/signup/` | User registration |
| `POST` | `/auth/login/` | User authentication |
| `GET`  | `/doctors/` | List all doctors |
| `POST` | `/appointments/book/` | Book an appointment |
| `GET`  | `/patients/{id}/` | Get patient details |

## 🛠️ Testing
To run tests:
```bash
cd backend
pytest  # For backend tests
```
```bash
cd frontend
npm test  # For frontend tests
```

## 📜 License
This project is licensed under the MIT License.

---

### ✨ **Contributions & Issues**
Feel free to fork this repo and submit pull requests. If you encounter issues, please report them in the Issues tab!

---

📩 **Maintainer:** [WhoAmInull](https://github.com/WhoAmInull)

