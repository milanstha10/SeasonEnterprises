# Season Enterprises

A modern full-stack business web application built with React, TypeScript, Node.js, Express, and MongoDB. The project provides a responsive and professional digital platform for Season Enterprises, with a separate frontend and backend architecture.

## 🌐 Live Demo

**Frontend:**
https://season-enterprises.vercel.app/

**Backend:**
Deployed on Render

**Source Code:**
https://github.com/milanstha10/SeasonEnterprises

---

## 📌 About the Project

Season Enterprises is a full-stack web application developed to create a modern online presence for a business.

The application follows a separated frontend/backend architecture:

* **Frontend:** React + TypeScript + Vite
* **Backend:** Node.js + Express.js
* **Database:** MongoDB
* **Frontend Deployment:** Vercel
* **Backend Deployment:** Render

The project focuses on responsive design, clean UI, API integration, authentication, database management, and production deployment.

---

## ✨ Features

* Responsive and modern user interface
* Full-stack frontend and backend architecture
* REST API integration
* MongoDB database integration
* User authentication
* JWT-based authentication
* Admin functionality
* Business information and content management
* Responsive navigation
* Reusable UI components
* Image/media integration
* Production-ready deployment
* Separate frontend and backend deployments

---

## 🛠️ Technologies Used

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* shadcn/ui
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* REST API

### Other Tools & Services

* Cloudinary
* Vercel
* Render
* Git & GitHub

---

## 🏗️ Project Structure

```text
SeasonEnterprises/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── lib/
│   │   └── ...
│   ├── package.json
│   └── vite.config.ts
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── ...
│   ├── package.json
│   └── server.js
│
└── README.md
```

---

## ⚙️ Getting Started

Follow the steps below to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/milanstha10/SeasonEnterprises.git
cd SeasonEnterprises
```

### 2. Set Up the Frontend

```bash
cd frontend
npm install
npm run dev
```

The frontend will start using the Vite development server.

### 3. Set Up the Backend

Open another terminal:

```bash
cd backend
npm install
npm run dev
```

The backend will start on the configured server port.

---

## 🔐 Environment Variables

Create the required environment files for the frontend and backend.

### Frontend

Example:

```env
VITE_API_URL=your_backend_api_url
```

### Backend

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

> Never commit your `.env` files or expose secret credentials in the repository.

---

## 🚀 Deployment

### Frontend — Vercel

The frontend is deployed using Vercel.

**Live website:**
https://season-enterprises.vercel.app/

### Backend — Render

The backend API is deployed separately using Render.

This architecture allows the frontend and backend to be independently deployed and maintained.

### Database — MongoDB

MongoDB is used as the primary database, with Mongoose providing schema modeling and database interaction from the Node.js backend.

---

## 🔄 Application Architecture

```text
                    ┌─────────────────────┐
                    │       User          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ React + TypeScript  │
                    │      Frontend       │
                    │      Vercel         │
                    └──────────┬──────────┘
                               │
                         REST API / Axios
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Node.js + Express   │
                    │       Backend       │
                    │       Render        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      MongoDB        │
                    │      Database       │
                    └─────────────────────┘
```

---

## 🔒 Security

The application uses several practices to protect application data and credentials:

* JWT-based authentication
* Environment variables for sensitive configuration
* Password protection/authentication mechanisms
* Backend API validation
* CORS configuration
* Secure database connection configuration

---

## 📱 Responsive Design

The application is designed to work across different screen sizes, including:

* 💻 Desktop
* 📱 Mobile
* 📟 Tablet

---

## 🎯 Project Goals

The main goals of this project were to:

1. Build a professional business website.
2. Create a scalable full-stack architecture.
3. Develop reusable React components.
4. Build and integrate backend REST APIs.
5. Connect the application to MongoDB.
6. Implement authentication and protected functionality.
7. Deploy the frontend and backend independently.
8. Gain practical experience with production deployment.

---

## 📚 What I Learned

Through this project, I gained practical experience with:

* Full-stack application development
* React and TypeScript
* REST API development
* Express.js backend architecture
* MongoDB and Mongoose
* JWT authentication
* API integration using Axios
* Responsive UI development
* Environment variable management
* CORS configuration
* Cloudinary integration
* Vercel deployment
* Render deployment
* Git and GitHub workflow

---

## 👨‍💻 Developer

**Milan Shrestha**

GitHub:
https://github.com/milanstha10

---

## 📄 License

This project is created for educational and portfolio purposes.

If you plan to reuse or distribute this project, please contact the author first.

---

⭐ If you find this project useful or interesting, consider giving the repository a star!
