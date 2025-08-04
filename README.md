# Pendown ✍️📚🎉  
An interactive platform built for college students to **share notes**, **convey messages**, and **organize events** — all in one place.

🚀 Live Demo: https://pendown27.netlify.app/
---

## 📌 Overview

**Pendown** is a web-based social platform crafted during **college** to empower students through collaborative learning and seamless communication. It aims to create a local digital hub for student interaction.

### 🌟 Features

- 📝 **Notes Sharing** – Upload and access study material curated by peers.
- 📢 **Announcements** – Post updates and important messages for everyone.
- 📅 **Event Organization** – Create, manage, and join college events.
- 💬 **Social Feed** – Stay connected with friends and class groups.
- 🔒 **Authentication** – Secure login system for personalized experiences.

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js (Planned / Under Development) -> completed 
- **Database**: MongoDB (Planned / Under Development) -> completed 
- **Hosting**: Netlify + Render

---

## 📷 Screenshots

> _Coming soon!_ Add UI screenshots here for better visual understanding.

---

## 📁 Folder Structure

```bash
LOCAL-FOR-VOCAL/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── App.js
├── backend/
│   ├── config/           # Database connection and environment setup
│   │   └── db.js
│   ├── controllers/      # Logic for handling routes
│   │   ├── noteController.js
│   │   ├── userController.js
│   │   └── eventController.js
│   ├── models/           # Mongoose schemas
│   │   ├── Note.js
│   │   ├── User.js
│   │   └── Event.js
│   ├── routes/           # Express route definitions
│   │   ├── noteRoutes.js
│   │   ├── userRoutes.js
│   │   └── eventRoutes.js
│   ├── middleware/       # Auth middleware or error handlers
│   │   └── authMiddleware.js
│   ├── .env              # Environment variables
│   ├── server.js         # Entry point of the backend
│   └── package.json
├── package.json
└── README.md

