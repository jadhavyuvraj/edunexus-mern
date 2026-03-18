# 🎓 EduNexus – School Management System

A modern, full-stack **School Management System** built with the **MERN stack (MongoDB, Express.js, React.js, Node.js)** to streamline academic operations, enhance communication, and simplify administration.

---

## ✨ Overview

EduNexus is designed to digitize and optimize school workflows — from managing students and teachers to tracking attendance, evaluating performance, and enabling seamless communication.

---

## 🔑 Key Features

### 👥 Role-Based Access

* **Admin** – Full control over system management
* **Teacher** – Manage classes, attendance, and student performance
* **Student** – View records, marks, and feedback

---

### 🛠 Admin Dashboard

* Add & manage students and teachers
* Create classes and subjects
* Manage system-wide settings

---

### 📊 Attendance Management

* Mark students as **Present/Absent**
* Generate attendance reports

---

### 📈 Performance Tracking

* Assign marks and feedback
* Monitor student progress over time

---

### 📉 Data Visualization

* Interactive charts and tables
* Easy performance insights

---

### 💬 Communication System

* Messaging between teachers and students
* Improves collaboration and engagement

---

## 🧰 Tech Stack

| Layer    | Technology                   |
| -------- | ---------------------------- |
| Frontend | React.js, Material UI, Redux |
| Backend  | Node.js, Express.js          |
| Database | MongoDB                      |

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Yogndrr/MERN-School-Management-System.git
cd MERN-School-Management-System
```

---

## 🌿 Branches Explained

* **main** → Latest improved architecture (recommended)
* **legacy-version** → Code from YouTube tutorial
* **community-version** → Community contributions

Switch branch:

```bash
git checkout legacy-version
```

---

## 🔧 Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```
MONGO_URL=mongodb://127.0.0.1/smsproject
SECRET_KEY=your_secret_key
```

Start backend:

```bash
npm start
```

---

## 🎨 Frontend Setup

```bash
cd frontend
npm install
```

Create `.env` file:

```
REACT_APP_BASE_URL=http://localhost:5000
```

Start frontend:

```bash
npm start
```

---

## 🗄 Database Setup

### Option 1: Local MongoDB

* Install MongoDB Community Server
* Run:

```bash
mongod
```

Connection string:

```
mongodb://127.0.0.1:27017/yourdbname
```

---

### Option 2: MongoDB Atlas (Recommended for Deployment)

* Create a cluster on MongoDB Atlas
* Use connection string:

```
mongodb+srv://<user>:<password>@cluster-url/dbname
```

---

## 🚀 Deployment

### Backend (Render)

* Create a Web Service
* Build command:

```
npm install
```

* Start command:

```
npm start
```

Add environment variables:

* `MONGO_URL`
* `SECRET_KEY`

---

### Frontend (Netlify / Vercel)

Build command:

```
npm run build
```

Publish directory:

```
build
```

Environment variable:

```
REACT_APP_BASE_URL=https://your-backend-url
```

---

## 🔗 Connecting Frontend & Backend

Update frontend `.env`:

```
REACT_APP_BASE_URL=https://your-backend.onrender.com
```

Rebuild after changes.

---

## 📌 Notes

* `legacy-version` → Matches YouTube tutorial
* `main` → Modern architecture (actively improving)
* `community-version` → Open for contributions

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a PR to the **community-version** branch.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🌟 Support

If you found this project helpful:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share it

---
