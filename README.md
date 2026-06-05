# 🛒 Full-Stack E-Commerce MERN App

A full-stack e-commerce web application built using the MERN stack — MongoDB, Express.js, React, and Node.js. The app supports user authentication, product browsing, and session management, and is deployed on Vercel.

---

## 🌐 Live Demo

- **Frontend:** [codesoft-frontend.vercel.app](https://codesoft-frontend.vercel.app)
- **Backend:** [codesoft-backend-eta.vercel.app](https://codesoft-backend-eta.vercel.app)

---

## 🗂️ Project Structure

```
ecommerce-mern-app/
├── frontend/       # React application
└── backend/        # Express.js REST API
```

---

## ⚙️ Tech Stack

| Layer     | Technology                        |
|-----------|-----------------------------------|
| Frontend  | React, Redux Toolkit, Tailwind CSS |
| Backend   | Node.js, Express.js               |
| Database  | MongoDB Atlas                     |
| Auth      | JSON Web Tokens (JWT), bcrypt     |
| Deployment| Vercel                            |

---

## 🚀 Running Locally

### Prerequisites
- Node.js installed
- MongoDB Atlas account
- A `.env` file in the `backend/` folder (see below)

### Backend `.env` setup
Create a file at `backend/.env` with the following:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FRONTEND_URL=http://localhost:3000
```

### Start the backend
```bash
cd backend
npm install
npm run dev
```

### Start the frontend
```bash
cd frontend
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📸 Screenshot

![App Screenshot](Full%20Stack%20E-Commerce%20MERN%20App.png)

---

## 📄 License

This project is for educational purposes.
