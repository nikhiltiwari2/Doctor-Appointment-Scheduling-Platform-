# Doctors Appointment Platform

A full-stack **Doctors Appointment Booking Platform** built using **Node.js, Express.js, MongoDB (backend)** and **React.js (frontend)**. This project allows users to register/login, book appointments with doctors, view available slots, and manage profiles. Doctors can manage appointments, approve/reject booking requests, and update their availability.

---

## 🚀 Features

### 👨‍⚕️ User Features

* User registration & login with JWT authentication
* Book appointments with doctors
* View booking history
* Profile management
* Safe password storage with hashing

### 🩺 Doctor Features

* Doctor registration / login
* Manage available slots
* Approve / reject appointments
* View upcoming bookings

### 🛠️ Admin Features

* Manage all doctors
* Manage users
* Approve doctor applications

### 🔒 Security

* Password hashing using bcrypt
* JWT-based secure authentication
* Role-based authorization

---

## 📂 Project Structure

```
doctors-appointment-platform/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Tech Stack

### **Frontend**

* React.js
* React Router
* Axios
* Tailwind / CSS

### **Backend**

* Node.js
* Express.js
* MongoDB with Mongoose
* JSON Web Token
* bcrypt

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/doctors-appointment-platform.git
cd doctors-appointment-platform
```

### 2️⃣ Backend Setup

```
cd backend
npm install
```

Create a **.env** file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=yourSecretKey
```

Run the backend server:

```
npm start
```

### 3️⃣ Frontend Setup

```
cd frontend
npm install
npm start
```

---

## 🔗 API Endpoints (Backend)

### **Auth Routes**

* POST `/api/auth/register`
* POST `/api/auth/login`

### **User Routes**

* GET `/api/user/profile`
* PUT `/api/user/profile/update`

### **Doctor Routes**

* POST `/api/doctor/apply`
* GET `/api/doctor/appointments`
* PUT `/api/doctor/approve/:id`
* PUT `/api/doctor/reject/:id`

### **Appointment Routes**

* POST `/api/appointment/book`
* GET `/api/appointment/user`

---

## 🧪 Future Improvements

* Online payment integration
* SMS/email notification system
* Advanced search filters
* Video consultation integration

---

## ⭐ Support the Project

If you like this project, don't forget to ⭐ the repository!
