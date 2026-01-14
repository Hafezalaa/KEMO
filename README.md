# KEMO


kemo/

├── client/        # React (FE)
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── server/        # Express / Node (BE)
│   ├── src/
│   ├── package.json
│   └── server.js
│
├── .gitignore
├── README.md



# KEMO – MERN Online Shop

A full-stack e-commerce platform built with the **MERN stack**  
(MongoDB, Express, React, Node.js)

---

## 🧠 Project Overview

KEMO is a scalable online shop featuring:
- Product catalog
- User authentication & authorization
- Cart & checkout flow
- Online payments
- Shipping management
- Email notifications
- Admin dashboard

---

## 🏗 Monorepo Structure

   Check it here [MonorepoStructure.md](MonorepoStructure.md)

## ✉️ Emailing

- SendGrid API
- Email templates:
  - Order confirmation
  - Shipping update
  - Password reset
  - Contact form confirmation

---

## 💳 Payments

- Stripe (primary)
- PayPal (optional)

---

## 🚚 Shipping

- Flat rate
- Weight-based shipping
- Future support:
  - DHL / UPS APIs
  - Tracking numbers

---

## 🔐 Authentication & Security

- JWT authentication
- Role-based access (User / Admin)
- Password hashing (bcrypt)
- Rate limiting
- Input validation
- Helmet & CORS

---

## 🧰 Main Dependencies

### Frontend
- react
- react-router-dom
- axios
- react-hook-form
- @tanstack/react-query
- tailwindcss
- react-icons
- react-toastify

### Backend
- express
- mongoose
- bcrypt
- jsonwebtoken
- cors
- dotenv
- helmet
- morgan
- express-validator
- multer
- cloudinary
- @sendgrid/mail
- stripe

---

## 🚀 Deployment

- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas
- Emails: SendGrid

---

## 📌 Status

This project is under active development.
