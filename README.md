# 📝 To-Do List App (MERN Stack)

A full-stack **MERN** (MongoDB, Express.js, React.js, Node.js) to-do list application that allows users to manage daily tasks, set deadlines, and track progress. Built to demonstrate full CRUD operations, authentication, and user-specific task management.

---

⚠️⚠️IMPORTANT :

## 🧱 MERN Stack Overview

This project is structured around the MERN stack:

- **MongoDB** – Database for storing tasks and users
- **Express.js** – RESTful API server
- **React** – (planned frontend)
- **Node.js** – Application runtime

The current version uses EJS as a placeholder UI, with all backend logic and MongoDB storage functioning like a typical MERN app.

⚠️⚠️deployment link:
https://to-do-app-jyws.onrender.com


## 🚀 Features

- ✅ User Registration and Login
- ✅ Create, Read, Update, Delete (CRUD) Tasks
- ✅ Deadline tracking
- ✅ MongoDB for persistent storage
- ✅ JWT-based authentication
- ✅ Fully responsive interface
- ✅ RESTful API integration

---

## 🧑‍💻 Tech Stack

| Layer      | Technology           |
|------------|----------------------|
| Frontend   | React.js (Vite/CRA)  |
| Backend    | Node.js + Express.js |
| Database   | MongoDB + Mongoose   |
| Auth       | JWT + bcryptjs       |
| Hosting    | Vercel + Render      |

---

## 📁 Folder Structure



to-do-app/
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── index.js
│
├── server/ # Node + Express backend
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── index.js
│
├── .env
├── package.json
├── README.md




1. Install Backend Dependencies
bash
Copy
Edit
cd server
npm install

Create a .env file in server/ with:
PORT=5000
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret

3. Install Frontend Dependencies
bash
Copy
Edit
cd ../client
npm install

4. Start the Application
Run Backend:

bash
Copy
Edit
cd server
npm start
Run Frontend:

bash
Copy
Edit
cd ../client
npm start
Go to http://localhost:3000

 Live Demo
👉 [Frontend (React) on Vercel]
👉 [Backend (API) on Render]

Screenshots:



 Notes
This project was developed as part of an internship to demonstrate full MERN stack capabilities including:

React.js SPA frontend

REST API with Express and Node

MongoDB backend with secure authentication



---
---



Author
Namrutha




