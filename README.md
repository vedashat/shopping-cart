# 🛒 Fullstack Shopping Cart App

A full-featured shopping cart web application built with a Go backend (Gin, GORM, JWT) and React frontend. This project was developed as part of a fullstack assignment.

---

## ✨ Features

### ✅ User Features
- User Login with JWT Authentication
- View item catalog
- Add items to cart
- Checkout cart to place orders
- View order history

### 🛠️ Admin Features
- Add/update/delete items (via DB or extended routes)
- View user orders

---

## 🔧 Tech Stack

| Layer        | Technology              |
|--------------|--------------------------|
| Frontend     | React.js, Axios, CSS     |
| Backend      | Go (Gin), GORM, JWT      |
| Database     | PostgreSQL               |
| Tools        | Postman (for API testing), VS Code

---

## 🗂️ Project Structure

shopping-cart/
├── backend/ # Go Gin backend
│ ├── main.go
│ ├── database/
│ ├── models/
│ └── routes/
├── frontend/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── App.js
│ │ └── index.js
└── README.md

## 🚀 Setup Instructions

### ✅ Backend (Go)

1. Navigate to backend folder:
   ```bash
   cd backend

🔁 API Endpoints
Auth
POST /users/login – Login user (returns JWT)

Items
GET /items – List all items

Cart (JWT Protected)
POST /carts – Add item to cart

GET /carts – View current cart

Orders (JWT Protected)
POST /orders – Checkout cart

GET /orders – View order history

Use Authorization: Bearer <token> header after login.

📫 Contact
Developer: Akshat Vedant
Feel free to connect for improvements or feedback.
