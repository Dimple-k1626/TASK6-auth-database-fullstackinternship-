# 🔐 Task 6 – Database Integration & User Authentication

This project demonstrates a **full-stack authentication system** with database integration, secure password handling, and protected routes.

The application allows users to **register, login, access a protected dashboard, and logout** using JSON Web Tokens (JWT).

---

## 🚀 Features

* User Registration with encrypted password
* User Login with authentication
* Secure password hashing using bcrypt
* JSON Web Token (JWT) authentication
* Protected dashboard page
* Logout functionality
* Session timer on dashboard
* User profile card displaying name and email
* Animated modern UI with gradient backgrounds

---

## 🛠 Technologies Used

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* bcryptjs
* JSON Web Token (JWT)
* dotenv

### Frontend

* HTML
* CSS
* JavaScript

---

## 📂 Project Structure

```
Task6-auth-database
│
├── client
│   ├── index.html
│   ├── dashboard.html
│   ├── style.css
│   ├── dashboard.css
│   └── script.js
│
├── server
│   ├── server.js
│   │
│   ├── config
│   │   └── db.js
│   │
│   ├── controllers
│   │   └── authController.js
│   │
│   ├── middleware
│   │   └── authMiddleware.js
│   │
│   ├── models
│   │   └── User.js
│   │
│   └── routes
│       └── authRoutes.js
│
├── .env
├── package.json
└── README.md
```

---

## ⚙ Installation and Setup

### 1️⃣ Clone the repository

```
git clone <repository-url>
```

### 2️⃣ Navigate to project folder

```
cd Task6-auth-database
```

### 3️⃣ Install dependencies

```
npm install
```

### 4️⃣ Configure environment variables

Create a `.env` file in the root directory.

Example:

```
MONGO_URI=mongodb://127.0.0.1:27017/authdb
JWT_SECRET=supersecretkey
```

---

## ▶ Running the Application

Start the backend server:

```
node server/server.js
```

If everything is correct, you should see:

```
MongoDB Connected
Server running on port 5000
```

---

## 🌐 Using the Application

1. Open the **client/index.html** file in your browser.
2. Register a new user.
3. Login with the registered credentials.
4. After successful login, you will be redirected to the dashboard.
5. The dashboard shows user information and session timer.
6. Click **Logout** to end the session.

---

## 🔐 Security Features

* Passwords are hashed using **bcrypt** before storing in the database.
* Authentication is handled using **JWT tokens**.
* Protected routes prevent unauthorized access to the dashboard.

---

## 🎨 UI Highlights

* Animated gradient backgrounds
* Glassmorphism dashboard card
* Modern login/register interface
* Responsive layout

---

## 📌 Future Improvements

* Password strength meter
* Email verification
* Dark/Light mode toggle
* User profile editing
* Deployment on cloud platforms

---

## 👨‍💻 Author

Project developed as part of **Level 3 Task 6 – Advanced Web Development Internship Task**.

---
