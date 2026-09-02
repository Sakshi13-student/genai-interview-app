# 🤖 GenAI Interview App

A full-stack AI-powered interview preparation application that generates personalized interview plans and questions based on a candidate's resume, job description, and self-description.

The application combines a React frontend, Node.js/Express backend, MongoDB database, and Generative AI to create an interactive interview preparation experience.

---

## 🚀 Features

- 🔐 User Registration and Login
- 🔑 JWT-based Authentication
- 🛡️ Protected Routes
- 📄 Resume Upload
- 💼 Job Description Input
- 👤 Candidate Self-Description
- 🤖 AI-powered Interview Report Generation
- 📝 Technical Interview Questions
- 🎯 Interview Preparation Based on Resume and Job Description
- 📊 Interview Report with Match Score
- 📥 Resume PDF Generation
- 🗄️ MongoDB Database Integration
- ⚡ React + Vite Frontend
- 🌐 REST API based Backend

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- React Router
- Axios
- SCSS

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Multer

### Generative AI

- Google Gemini API
- Structured AI responses
- Zod schema validation

---

## 📁 Project Structure

```text
GenAI fullstack project/
│
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── database.js
│   │   │
│   │   ├── controllers/
│   │   │   ├── auth.controller.js
│   │   │   └── interview.controller.js
│   │   │
│   │   ├── middlewares/
│   │   │   ├── auth.middleware.js
│   │   │   └── file.middleware.js
│   │   │
│   │   ├── models/
│   │   │   ├── blacklist.model.js
│   │   │   ├── interviewReport.model.js
│   │   │   └── user.model.js
│   │   │
│   │   ├── routes/
│   │   │   ├── auth.routes.js
│   │   │   └── interview.routes.js
│   │   │
│   │   ├── services/
│   │   │   ├── ai.service.js
│   │   │   └── temp.js
│   │   │
│   │   └── app.js
│   │
│   ├── .env
│   ├── .gitignore
│   ├── package.json
│   └── server.js
│
├── Frontend/
│   ├── src/
│   │   ├── features/
│   │   │   ├── auth/
│   │   │   └── interview/
│   │   │
│   │   ├── style/
│   │   ├── App.jsx
│   │   ├── app.routes.jsx
│   │   └── main.jsx
│   │
│   ├── public/
│   ├── .gitignore
│   ├── package.json
│   └── vite.config.js
│
└── README.md
