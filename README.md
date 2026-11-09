# 📦 Inventory Management System

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

## 📖 About the Project

The Inventory Management System is a full-stack web application designed to manage business inventory, products, purchases and sales.

It provides a React-based frontend connected to a REST API built using Node.js, Express and TypeScript, with MongoDB for database storage.

The project was developed as part of my personal web development practice to strengthen my understanding of full-stack application development.

## ✨ Features

- 🔐 User authentication and protected API routes
- 📦 Product management
- 🏷️ Product categories and brands
- 🛒 Purchase management
- 💰 Sales management
- 📊 Sales analytics with daily, weekly, monthly and yearly reporting
- ✅ Request validation
- 🗄️ MongoDB database integration
- 💻 React frontend with reusable components

## 🛠️ Technologies Used

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Ant Design
- Redux Toolkit
- React Router
- Axios
- Recharts
- React Icons

### Backend
- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- JSON Web Tokens (JWT)
- bcrypt
- Zod

## 📁 Project Structure

```text
inventory-management-system/
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── middlewares/
│   │   └── modules/
│   ├── package.json
│   └── ...
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- MongoDB (local installation or Atlas)
- Git

### 1. Clone the repository

```bash
git clone https://github.com/ShauryaParmar2102/inventory-management-system-full-application.git

cd inventory-management-system-full-application
```

### 2. Install backend dependencies

```bash
cd backend
npm install
```

Configure the required backend environment variables before starting the server.

```bash
npm run dev
```

### 3. Install frontend dependencies

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Ensure the frontend is configured to communicate with your running backend API.

## 🔮 Future Improvements

The following features are planned for future development:

- [ ] 👥 **Customer Role** — Allow customers to register, log in, browse available products and view their orders.
- [ ] 🛒 **Shopping Cart** — Allow customers to add products to a cart before checkout.
- [ ] 📋 **Customer Order History** — Let customers track previous purchases and order statuses.
- [ ] 🔔 **Low Stock Notifications** — Alert administrators when inventory quantities fall below a specified threshold.
- [ ] 📱 **Mobile Responsiveness** — Further improve the experience across different screen sizes.

## 🎯 Project Goals

The main goals of this project are to:

- Improve my React and TypeScript development skills.
- Gain more experience building REST APIs with Express.
- Practise MongoDB database integration.
- Strengthen my understanding of authentication, validation and CRUD operations.
- Build and maintain full-stack applications for my GitHub portfolio.

## 👨‍💻 Developer

Developed by **Shaurya Parmar**

[GitHub Profile](https://github.com/ShauryaParmar2102)

This project was built for learning, experimentation and continued development.
