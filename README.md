# 📚 BookNest — Digital Library Web App

BookNest is a full-stack digital library platform designed to make discovering, borrowing, and managing books simple and interactive. It combines a clean user interface with powerful backend functionality, allowing users to explore books, leave reviews, and track activity, while admins gain insights through data visualizations.

---

## 🚀 Features

### 👤 User Features
- User authentication (signup/login)
- Browse and search books
- Filter books by category/genre
- Borrow and return books with limits
- Leave ratings and reviews
- View borrowing history

### 📊 Admin Dashboard
- Book ratings visualization (D3.js)
- Borrowing trends and overdue tracking
- Insights into total books vs borrowed vs overdue
- Manage book inventory

### 🔍 Smart Capabilities
- OCR-based text extraction (Tesseract.js)
- Dynamic charts using D3.js
- Real-time updates between frontend and backend

---

## 🛠️ Tech Stack

Frontend
- React (Vite)
- HTML, CSS, JavaScript
- D3.js

Backend
- Node.js
- Express.js

Database
- MongoDB

Other Tools
- Tesseract.js
- REST APIs

---

## ⚙️ Getting Started

### 1. Start the Frontend

cd booknest
npm install
npm run dev

---

### 2. Start the Backend

Make sure MongoDB is running locally

cd server

Create a `.env` file:

MONGODB_URI=mongodb://localhost:27017/booknest
PORT=5000

Then run:

npm install
npm run seed
npm run dev

---

## 📦 Requirements

- Node.js (v16+ recommended)
- MongoDB (local or Atlas)
- npm or yarn

---

## 🧠 What I Learned

- Built a full-stack application connecting a React frontend with a Node.js and Express backend
- Worked with MongoDB for data storage, queries, and schema design
- Implemented authentication and user-based features like borrowing and reviews
- Created interactive data visualizations using D3.js
- Integrated OCR functionality to extend application capabilities
- Improved debugging, project structuring, and team collaboration skills

---

## 🔧 What I Would Improve

- Improve UI/UX with more polished design and smoother interactions
- Add real-time features (e.g., live updates for borrowing activity)
- Optimize backend and database performance for scalability

---

## 📌 Project Highlights

- Clean full-stack architecture
- Real-world use case (digital library system)
- Data visualization for insights
- Combines multiple technologies (OCR + charts + backend APIs)

---

## 🎯 Why This Project Matters

BookNest showcases my ability to build practical, scalable applications that combine backend systems, frontend design, and data-driven features. It reflects my interest in full-stack development, data visualization, and creating tools that simplify complex information.

---

## 🎥 Demo
[![BookNest Demo](https://youtube.com/shorts/7zfSZHZeoTo](https://youtu.be/FMYDMg9ox-o))
