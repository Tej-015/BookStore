# 📚 Book Store Management System

A full-stack Book Store Management System built using the MERN Stack. The application provides separate modules for **Admin**, **Seller**, and **User**, allowing complete management of books, orders, and users.

---

## 🚀 Live Demo

🌐 Frontend: https://book-store15.vercel.app/

---

## 📌 Features

### 👤 User
- User Registration & Login
- Browse Books
- Search Books
- View Book Details
- Add Books to Wishlist
- Place Orders
- View Order History

### 🛍 Seller
- Seller Registration & Login
- Add New Books
- Update Book Details
- Delete Books
- View Products
- View Customer Orders

### 👨‍💼 Admin
- Admin Registration & Login
- Dashboard
- Manage Users
- Manage Sellers
- Manage Books
- View Orders
- Analytics Dashboard

---

# 🛠 Tech Stack

## Frontend
- React.js
- Vite
- React Router DOM
- Axios
- Tailwind CSS
- Recharts

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- Cookie Parser
- CORS

---

# 📂 Project Structure

```
Book-Store
│
├── client
│   ├── src
│   │   ├── Admin
│   │   ├── Seller
│   │   ├── User
│   │   ├── Components
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── server
│   ├── config
│   ├── controllers
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── uploads
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/Tej-015/Book-Store.git
```

```bash
cd Book-Store
```

---

## Backend Setup

```bash
cd server
```

Install dependencies

```bash
npm install
```

Create a `.env` file

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

Run backend

```bash
npm start
```

or

```bash
npx nodemon server.js
```

---

## Frontend Setup

Open another terminal

```bash
cd client
```

Install dependencies

```bash
npm install
```

Run frontend

```bash
npm run dev
```

Open

```
http://localhost:5173
```

---

# 📦 Frontend Packages

```bash
npm install react-router-dom axios
npm install recharts
npm install react-icons
npm install tailwindcss @tailwindcss/vite
```

---

# 📦 Backend Packages

```bash
npm install express mongoose cors dotenv jsonwebtoken multer cookie-parser
npm install --save-dev nodemon
```

---

# 🔐 Authentication

- JWT Authentication
- HTTP Only Cookies
- Protected Routes
- Role-based Authorization

---

# 📈 Dashboard

The Admin Dashboard includes

- Total Users
- Total Sellers
- Total Books
- Total Orders
- Graphical Statistics using Recharts

---

# 🖼 Screenshots

### Home Page

- Landing Page
- Categories
- Navigation

### Admin Panel

- Login
- Registration
- Dashboard
- User Management
- Seller Management
- Books Management

### Seller Panel

- Dashboard
- Products
- Orders

### User Panel

- Browse Books
- Wishlist
- Orders

---

# 🌐 Deployment

Frontend

- Vercel

Backend

- Render

Database

- MongoDB Atlas

---

# 👨‍💻 Author

**Yuva Teja**

GitHub

https://github.com/Tej-015

LinkedIn

https://www.linkedin.com/in/yuva-teja-4527132b2/

---

# ⭐ If you like this project

Please give this repository a ⭐ on GitHub.
