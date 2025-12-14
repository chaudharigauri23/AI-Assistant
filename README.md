# AI-Assistant
🤖 Virtual AI Assistant

A Full-Stack AI Assistant Application

An intelligent AI-powered assistant built using MERN stack, integrated with OpenAI, MongoDB Atlas, and Cloudinary, offering secure authentication, media handling, and real-time AI responses.

✨ Features

🧠 AI-powered conversational assistant

🔐 Secure JWT-based authentication

🗄️ MongoDB Atlas cloud database

☁️ Cloudinary media/file storage

⚡ Fast frontend using modern tooling

🛡️ Environment-based secure configuration

🧩 Tech Stack

Frontend: React, Vite
Backend: Node.js, Express
Database: MongoDB Atlas
AI Engine: OpenAI API
Storage: Cloudinary
Auth: JWT

📋 Prerequisites

Make sure you have the following installed:

🟢 Node.js (LTS version)

🗄️ MongoDB Atlas account

🔐 Required API Keys (details below)

📥 Project Setup
🔹 Step 1: Clone the Repository
git clone https://github.com/Omkarkawale045/Virtual-AI-Assistant.git
cd Virtual-AI-Assistant

⚙️ Backend Configuration
🔹 Step 2: Install Backend Dependencies
cd backend
npm install

🔐 Environment Variables Setup

Inside the backend folder, create a .env file:

MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret


🚫 Do not upload .env to GitHub
Add this to .gitignore:

.env
/node_modules

🗄️ MongoDB Atlas Setup

Visit 👉 https://www.mongodb.com/cloud/atlas

Create a free cluster

Add database user (username & password)

Whitelist IP: 0.0.0.0/0

Click Connect → MongoDB Driver

Copy connection string

Replace password & paste into MONGO_URI

🔑 API Keys Configuration
Service	Purpose
OpenAI	AI responses
Cloudinary	Media storage
JWT Secret	User authentication
Generate JWT Secret
node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"

▶️ Run Backend Server
npm run dev


📍 Backend URL:

http://localhost:5000

🎨 Frontend Setup
🔹 Step 3: Install & Run Frontend
cd ../frontend
npm install
npm run dev


📍 Frontend URL:

http://localhost:5173

🛠 Optional: Admin Panel

If included in the project:

cd admin
npm install
npm run dev


📍 Admin Panel URL:

http://localhost:5174

✅ Project Status Checklist

✔ Backend running

✔ Frontend running

✔ MongoDB connected

✔ API keys configured

✔ No terminal errors

🎉 Your Virtual AI Assistant is live!

🛡 Security Guidelines

Never commit or share:

.env files

Database credentials

API keys

Authentication tokens

Always use environment variables for sensitive data.

📌 Summary

This project delivers a secure, scalable AI assistant with cloud storage, authentication, and AI intelligence — ready for development, deployment, or extension.
