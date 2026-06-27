# 🛒 Snack-X Ecommerce Store

> A modern full-stack eCommerce web application built using React, Node.js, Express, MongoDB, and Razorpay for seamless online shopping and secure payments.

Snack-X provides users with an intuitive shopping experience where they can browse products, manage their cart, securely checkout using Razorpay, and view previous orders.

---

# 📌 Overview

Snack-X is a responsive full-stack eCommerce application developed as part of the **CodeAlpha Internship Program**.

The project demonstrates modern web development practices by integrating a React frontend with a Node.js/Express backend, MongoDB database, and Razorpay payment gateway.

---

# ✨ Features

## 👤 User Authentication

- User Registration
- Secure Login
- User Session Management

---

## 🛍 Product Catalog

- Browse Products
- Product Search
- Responsive Product Cards
- Dynamic Product Listing

---

## 🛒 Shopping Cart

- Add to Cart
- Remove from Cart
- Update Quantity
- Cart Total Calculation
- Persistent Cart

---

## 💳 Secure Checkout

- Razorpay Payment Gateway
- Order Confirmation
- Payment Verification
- Success Page

---

## 📦 Orders

- Order History
- View Previous Purchases

---

## 🎨 User Experience

- Fully Responsive Design
- Modern UI
- Fast Navigation
- Mobile Friendly

---

# 🛠 Tech Stack

## Frontend

- React 19
- React Router DOM
- Vite
- JavaScript
- CSS3

---

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Razorpay API
- dotenv
- CORS

---

# 📂 Project Structure

```
Snack-X
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server/
│   ├── data/
│   ├── models/
│   ├── server.js
│   ├── seed.js
│   └── package.json
│
├── package.json
└── README.md
```

---

# 🚀 Features Included

- Responsive Homepage
- Product Listing
- Product Search
- Shopping Cart
- Checkout
- Razorpay Integration
- User Authentication
- MongoDB Database
- Order Management
- REST API
- Mobile Responsive Design

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/Apoorv-Gaurav/CodeAlpha_EcommerceStore.git

cd CodeAlpha_EcommerceStore
```

---

## Install Dependencies

```bash
npm install
```

---

## Install Client

```bash
cd client

npm install
```

---

## Install Server

```bash
cd ../server

npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the **server** directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

RAZORPAY_KEY_ID=your_key_id

RAZORPAY_KEY_SECRET=your_key_secret
```

---

# ▶ Running the Project

## Start Both Client and Server

```bash
npm run dev
```

---

Or start individually.

### Backend

```bash
npm run server
```

### Frontend

```bash
npm run client
```

---

Open

```
http://localhost:5173
```

---

# 💳 Payment Gateway

Snack-X integrates **Razorpay** for secure online payments.

Features include:

- Secure Payment Processing
- Payment Verification
- Order Confirmation
- Success Page

---

# 🗄 Database

MongoDB Atlas is used for storing:

- User Accounts
- Orders
- Purchase History

Product information is served from a static catalog.

---

# 📸 Screenshots

Add screenshots of the application here.

Example:

```
screenshots/

├── homepage.png
├── products.png
├── cart.png
├── checkout.png
├── payment.png
├── orders.png
```

---

# 🌟 Future Improvements

- Wishlist
- Product Categories
- Product Reviews
- Admin Dashboard
- Inventory Management
- Coupon System
- Email Notifications
- User Profiles
- Dark Mode
- Product Filtering
- Order Tracking

---

# 🔒 Security

- Secure Environment Variables
- MongoDB Atlas Integration
- Razorpay Payment Verification
- Protected Backend APIs

---

# 👨‍💻 Author

**Apoorv Gaurav**

GitHub:  
https://github.com/Apoorv-Gaurav

---

# 📄 License

This project was developed as part of the **CodeAlpha Internship Program** and is intended for educational and portfolio purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
