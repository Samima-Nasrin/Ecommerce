# e-Commerce Clothing Store (MERN)

A **full-stack eCommerce application** built with the **MERN stack**, featuring authentication, PayPal payment integration, cart management, order tracking, and a dedicated admin panel for managing products, users, and orders.

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Run Locally](#run-locally)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)

---

## Features

### User Side
- **Authentication & Authorization**  
  - User signup, login, and logout using **JWT** and **cookies**.  
  - Role-based access control (Admin/User).  

- **Product Management**  
  - Browse products with **pagination**, **search**, and **filters**.  
  - Product details page with size and quantity selection.

- **Cart & Checkout**  
  - Add, update, or remove products from the cart.  
  - Save delivery addresses for future use.  
  - Order summary displayed before payment.

- **Payment Integration**  
  - **PayPal API** integration for secure payments.  
  - Order tracking and confirmation after payment.

---

### Admin Panel
- **Dashboard Overview**  
  - View total sales, orders, and products at a glance.

- **Product Management**  
  - Add, update, or delete products with **image uploads**.  
  - Manage product categories and stock inventory.

- **Order Management**  
  - View, update, and filter orders based on **payment** and **delivery status**.

- **User Management**  
  - View all registered users and their roles.  
  - Update user roles (e.g., promote users to admin).

---

##  Tech Stack
- **Frontend:** React.js, Redux, CSS, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  
- **Authentication:** JWT, Cookies  
- **Payment Gateway:** PayPal API  
- **Hosting:**  
  - Frontend: Vercel / Netlify  
  - Backend: Heroku / Render  
  - Database: MongoDB Atlas

---

## Installation

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/ecommerce-clothing-store.git
   cd ecommerce-clothing-store

cd server && npm install  
cd client && npm install  

