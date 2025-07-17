# 🛒 ShopSmart: Your Digital Grocery Store Experience

**Team ID:** LTVIP2025TMID57814  
**Developer:** J. Hemanth (`234E1A4727`)  
**Repository:** [GitHub - ShopSmart-Project](https://github.com/JHemanth2005/ShopSmart-Project)

---

## 📖 Introduction

**ShopSmart** is a full-featured, modern grocery store web application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It aims to transform traditional grocery shopping into a seamless digital experience for users and vendors.

With a responsive UI, real-time inventory updates, secure login, and role-based access, **ShopSmart** makes daily grocery management easy and efficient.

---

## ✨ Key Features

### 👨‍👩‍👧‍👦 Users
- Secure registration and login (JWT-based)
- Browse and search products by category
- Add to cart and place orders
- View order history
- Update profile and delivery details

### 🧑‍💼 Admin
- Role-based access for product and user management
- Add/Edit/Delete grocery items
- Update product categories and stock
- Track and manage all orders
- View and respond to user queries

---

## ⚙️ Tech Stack

| Layer       | Technology                                   |
|-------------|----------------------------------------------|
| Frontend    | React.js, Axios, React Router, Bootstrap, Material-UI |
| Backend     | Node.js, Express.js                          |
| Database    | MongoDB with Mongoose ODM                    |
| Authentication | JWT (JSON Web Tokens), Bcrypt             |
| Architecture| MVC Pattern                                  |

---

## 🗃️ Project Structure

```
/shop-mart
├── client
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       ├── context
│       ├── services
│       └── App.js
├── server
│   ├── models
│   ├── routes
│   ├── controllers
│   ├── middleware
│   └── server.js
```

---

## 🛒 Application Workflow

### Users
1. Register/Login
2. Browse products
3. Add items to cart
4. Checkout and place orders
5. View order history
6. Manage delivery details

### Admins
1. Login with secure credentials
2. Manage product listings
3. Monitor orders and inventory
4. Manage users and access roles
5. Handle customer queries

---

## 🛡️ Security & Performance

- Passwords hashed using **Bcrypt**
- JWT used for **secure sessions**
- **Role-based access** control
- CORS enabled for API security
- **Lazy loading** in React
- **MongoDB indexing** for faster queries
- **Code splitting & minification** for performance

---

## 🧩 Database Schema Overview

### Collections
- **Users**: ID, Name, Email, Password, Role, Address
- **Products**: ID, Name, Category, Price, Stock, ImageURL, Description
- **Cart**: CartID, UserID, ProductID, Quantity
- **Orders**: OrderID, UserID, Products[], Amount, Date, Status, DeliveryAddress
- **Admins**: Inherits from User with elevated privileges

---

## 🚀 Setup & Installation

### Prerequisites
- Node.js & npm
- MongoDB (Local or Atlas)
- Git & GitHub
- React with Create React App
- Postman (for API testing)

### Local Setup

```bash
# Clone the repository
git clone https://github.com/JHemanth2005/ShopSmart-Project.git

# Backend Setup
cd ShopSmart-Project/server
npm install
npm run dev

# Frontend Setup
cd ../client
npm install
npm start
```

---

## 📷 UI Screens (Add in your repo)
- ✅ Home Page
- ✅ Login & Signup Forms
- ✅ Product Listing with Filters
- ✅ Cart and Checkout Flow
- ✅ Order Confirmation & History
- ✅ Admin Dashboard (CRUD)
- ✅ Mobile Responsive Views

---

## 🔮 Future Enhancements

- 🔐 OTP-based login system
- 💳 Payment Gateway Integration (Razorpay/Stripe)
- 📲 Native app using React Native
- 🤖 Chatbot and customer support
- 📈 Admin analytics dashboard
- 🧠 AI-powered product recommendations
- 🚚 Live order tracking and delivery partner support

---

## 📦 Deployment

- Frontend: Netlify / Vercel  
- Backend: Render / Heroku  
- Database: MongoDB Atlas

---

## 📽️ Demo

```
Demo File: C:\Users\hemanth\video-demo\video-5q7189-3e34.mp4
```

---

## 🔗 Links

- 📂 GitHub Repository: [https://github.com/JHemanth2005/ShopSmart-Project](https://github.com/JHemanth2005/ShopSmart-Project)

---

## 📌 Conclusion

**ShopSmart** empowers users with a smooth online shopping experience and equips vendors with a reliable digital platform. It showcases the power of full-stack JavaScript and is scalable for future growth and innovation.

> Developed with ❤️ by **The Shop Mart Team**  
> Empowering Local Stores Through Technology
