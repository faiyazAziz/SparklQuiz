
# 📝 Online Quiz System

This is a **full-stack Online Quiz System** built using **Django (DRF) for the backend** and **React (with Redux) for the frontend**.

---

## 🚀 **Project Setup Guide**

### 🔹 **1. Clone the Repository**
```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

---

## 🛠 **Backend (Django) Setup**

### 🔹 **2. Navigate to Backend Folder**
```bash
cd backend
```

### 🔹 **3. Create & Activate Virtual Environment**
```bash
# Create virtual environment
python -m venv venv  

# Activate (Windows)
venv\Scripts\activate  

# Activate (Mac/Linux)
source venv/bin/activate  
```

### 🔹 **4. Install Dependencies**
```bash
pip install -r requirements.txt
```

### 🔹 **5. Apply Migrations & Run Server**
```bash
python manage.py migrate
python manage.py runserver
```

✅ **Django server is now running at** 👉 `http://127.0.0.1:8000/`
**Note: If not running on port 8000

---

## ⚛️ **Frontend (React) Setup**

### 🔹 **6. Navigate to Frontend Folder in new terminal**
```bash
cd frontend
```

### 🔹 **7. Install Dependencies**
```bash
npm install
```

### 🔹 **8. Run React Development Server**
```bash
npm run dev
```

✅ **React frontend is now running at** 👉 `http://localhost:5173/` (or your configured port)

---

## 🎯 **API Endpoints**

📌 **Backend API Base URL** 👉 `http://127.0.0.1:8000/api/`

### 🔹 **Authentication**
- `POST /api/login/` - User login  
- `POST /api/register/` - User registration  
- `GET /api/user/` - Get current user  

### 🔹 **Quiz Management**
- `GET /api/quizzes/` - Get all quizzes  
- `POST /api/quizzes/` - Create a new quiz (Admin)  
- `GET /api/quizzes/{id}/` - Get quiz details  

### 🔹 **Quiz Attempt & Submission**
- `POST /api/my-quizzes/{id}/start/` - Start a quiz  
- `POST /api/my-quizzes/{id}/submit/` - Submit a quiz attempt  
- `GET /api/my-quizzes/{id}/response/` - Get user quiz responses  

### 🔹 **Admin Features**
- `GET /api/quizzes/{id}/participants/` - Get all participants of a quiz  
- `GET /api/quizzes/{id}/response/{participant_id}/` - Get a participant’s responses  

---

## 📌 **Tech Stack**
- **Backend:** Django, Django REST Framework (DRF), PostgreSQL, JWT Authentication  
- **Frontend:** React, Redux, Bootstrap, React Router  
- **Others:** JWT, CORS, Axios  

---

## ✅ **Ready to Use! 🎉**
Now, open your **browser** and start using the **Online Quiz System**! 🚀  

Let me know if you need any modifications! 🔥

