🚀 Project Setup & Contribution Guide

Welcome to the project! This guide will help you set up the project locally and start contributing smoothly.

📌 Prerequisites

Make sure you have the following installed on your system:

Node.js (LTS recommended)
MongoDB
Git
📚 Recommended Knowledge

Before contributing, it is helpful to understand:

Node.js
React
Express.js
MongoDB
📦 Project Installation
1. Clone the Repository
git clone https://github.com/your-username/your-repo.git
cd your-repo
🖥️ Backend Setup
Navigate to backend
cd backend
Install dependencies
npm install
Environment variables

Create a .env file in the backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

You may also copy from .env.example if available.

Run backend server
npm run dev
🎨 Frontend Setup
Navigate to frontend
cd ../frontend
Install dependencies
npm install
Start development server
npm start
🌐 Application Access

Once both servers are running:

Frontend: http://localhost:3000
Backend: http://localhost:5000
🧪 Environment Example
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
🤝 Contributing Guidelines

We welcome contributions from everyone!

Steps to contribute:
Fork the repository

Create a new branch

git checkout -b feature/your-feature-name
Make your changes

Commit your changes

git commit -m "feat: add your message here"

Push to GitHub

git push origin feature/your-feature-name
Open a Pull Request