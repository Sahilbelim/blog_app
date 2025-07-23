# blog app - MERN Stack Blog Application

Welcome to **Blog App**, a full-featured blog platform built using the **MERN stack** (MongoDB, Express.js, React, Node.js). Developed by **Sahilbelim**, this application allows users to create, manage, and explore blog posts through a clean and user-friendly interface.

**🔗 Live Demo:** [blog app on Render] 

---

## 🚀 Features

- User authentication (Email/Password + Google OAuth)
- Create, edit, and delete blog posts
- Admin dashboard for managing users, posts, and comments
- Rich text editor for blog content
- Keyword search and filtering
- Responsive UI with protected routes

---

## 🧾 Project Structure


---

## 📚 Key Pages & Functionality

### ✅ Home Page
Displays latest blog posts with navigation options.

### 🔐 Authentication
- **Sign Up / Sign In** with Email/Password or Google
- Secure JWT-based sessions

### 📝 Post Management
- Authenticated users can create and update their own posts
- Admin users can manage all content

### 🔍 Search & Filter
Search posts by keyword, and optionally filter by tags or categories.

### 📊 Admin Dashboard
- View and manage all posts, users, and comments
- Admin-only access

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Sahil/blog_app.git
cd blog_app

# For backend
cd server
npm install

# For frontend
cd ../client
npm install

Create a .env file in the /server directory with the following:

MONGODB_URI=mongodb://localhost:27017/<your-db-name>
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# Start backend
cd server
npm run dev

# Start frontend
cd ../client
npm start

Made with ❤️ by Sahilbelim"# blog_app" 
