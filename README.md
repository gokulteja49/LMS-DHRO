# DHRO – Learning Management System

This is a full-stack LMS (Learning Management System) project built with the **MERN stack**, offering mock tests, courses, blogs, PDFs, and daily learning resources.

> Developed by Gokul Teja

---

## Getting Started

### 📦 Backend Setup

First, navigate to the backend folder and install dependencies:

```bash
cd backend
npm install
```

Then run the backend server:

```bash
npm start
```

> Ensure you create a `.env` file in the `backend` directory with the following:

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
PORT=5000
```

---

### 💻 Frontend Setup

Open a new terminal and navigate to the frontend folder:

```bash
cd frontend
npm install
```

Then start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the app running.

You can start editing the app from the `pages/` or `app/` directory depending on your Next.js version.

---

## 📚 Features

- 📖 View and enroll in online/offline courses  
- 🧪 Attempt mock tests and track performance  
- 📰 Read blogs and daily current affairs  
- 📥 Download books and study PDFs  
- 🔐 Secure login with JWT authentication  
- 🧑‍💼 Admin controls for content management  

---
