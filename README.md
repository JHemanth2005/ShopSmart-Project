# 🛒 ShopSmart: Digital Grocery Store (MERN Stack Project)

**Team ID:** LTVIP2025TMID57814  
**Developer:** J. Hemanth – [234E1A4727]  
**GitHub Repo:** [Click Here](https://github.com/JHemanth2005/ShopSmart-Project)

---

## 📌 What is ShopSmart?

**ShopSmart** is a modern web application built with the **MERN stack** (MongoDB, Express, React, Node) that brings your local grocery store experience online.

This project focuses on two main users:
- 🧑‍💻 **Customers** who want to browse and order groceries online.
- 🧑‍💼 **Admins/Vendors** who want to manage their product inventory and customer orders easily.

---

## 🚀 Key Features

### ✅ For Customers:
- Register/Login securely
- Search and filter products
- Add items to cart
- Place orders and track them
- View order history
- Update delivery address

### 🛠️ For Admins:
- Secure admin login
- Add/Edit/Delete products
- View and manage all orders
- Update stock and product details
- Manage customers

---

## ⚙️ Tech Stack

| Layer       | Tech Used                          |
|-------------|------------------------------------|
| Frontend    | React.js, Axios, Bootstrap, Material-UI |
| Backend     | Node.js, Express.js                |
| Database    | MongoDB with Mongoose              |
| Auth        | JWT + Bcrypt for secure login      |
| Architecture| MVC (Model-View-Controller)        |

---

## 🧠 Real-Life Scenarios

**👨‍💼 Ravi (Customer):** Busy with work, he shops online using ShopSmart. Filters, adds to cart, confirms delivery with admin, and checks out smoothly.

**👩‍🌾 Lakshmi (Vendor):** Lists her local store products, gets more customers, tracks orders in real-time, and grows her business.

---

## 🗂️ Project Structure

```
/shop-mart
├── client (React Frontend)
│   └── src → components, pages, context, services
├── server (Node Backend)
│   └── models, routes, controllers, middleware
```

---

## 🛠️ How to Run This Project

### 🔧 Requirements:
- Node.js & npm
- MongoDB (local or Atlas)
- Git
- VS Code or any IDE

### 📦 Installation:

```bash
git clone https://github.com/JHemanth2005/ShopSmart-Project.git
cd ShopSmart-Project

# Backend Setup
cd server
npm install

# Frontend Setup
cd ../client
npm install

# Start frontend and backend separately
npm start
```

---

## 📊 Database Schema Overview

- **Users:** ID, Name, Email, Role (user/admin)
- **Products:** ID, Name, Category, Price, Stock, Image
- **Cart:** CartID, UserID, ProductID, Quantity
- **Orders:** OrderID, UserID, Products[], Status, Amount

---

## 🔐 Security & Optimizations

- Passwords encrypted with **Bcrypt**
- **JWT tokens** for session management
- Role-based access control
- API protected with middleware
- Lazy loading + code splitting for performance

---

## 📸 Expected Screens (Screenshots)
- Landing Page
- Login/Register
- Product Listing
- Cart Page
- Checkout Flow
- Order History
- Admin Dashboard
- Mobile Responsive Views

---

## 📈 Future Improvements
- Payment integration (Stripe/Razorpay)
- OTP-based login
- Chat support and bot
- Mobile app (React Native)
- Live order tracking for delivery
- Admin analytics with charts

---

## 🏁 Final Thoughts

**ShopSmart** shows how full-stack development can digitize small businesses. It’s simple for customers, powerful for vendors, and scalable for future features.

> 💡 "A grocery store in your browser – fast, secure, and local!"

---

## 🔗 Links

- 💻 Source Code: [https://github.com/JHemanth2005/ShopSmart-Project](https://github.com/JHemanth2005/ShopSmart-Project)
- 🎬 Demo Video (Local Path): `C:\Users\hemanth\video-demo\video-5q7189-3e34.mp4`

---

🧑‍💻 **Developed with MERN Stack**  
⚡ Empowering Local Stores Through Technology  
~ **The Shop Mart Team**
