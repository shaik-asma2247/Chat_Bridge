
# 🧠 ChatBridge — Real-time Chat Application

Live Website 👉 [ChatBridge on Render](https://chat-bridge-zpy5.onrender.com)

## 📌 Overview

**ChatBridge** is a real-time chat application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and integrated with **Socket.IO** for instant communication. It allows users to sign up, log in, and engage in live one-on-one conversations.

---

## 🚀 Features

* 🔐 **User Authentication** (Sign up, Log in, Log out)
* 📬 **Real-Time Messaging** with Socket.IO
* 🧾 **Chat History** persistence with MongoDB
* ✅ **Protected Routes** for authenticated sessions
* 💻 **Responsive UI** built with modern React
* 🌐 **Deployed** on Render

---

## 🛠️ Tech Stack

### ⚙️ Backend

* **Node.js**
* **Express.js**
* **MongoDB** with Mongoose
* **Socket.IO**
* **JWT** for authentication
* **dotenv** for environment configuration

### 🌐 Frontend

* **React.js**
* **React Router**
* **Axios** for API calls
* **Zustand** for state management
* **Tailwind CSS** (optional based on your styling)

---

## 🏗️ Folder Structure (Short Overview)

```
📁 client/         # Frontend (React)
📁 server/         # Backend (Express)
 ├── routes/       # API route handlers
 ├── controllers/  # Logic behind each route
 ├── models/       # MongoDB schemas
 ├── lib/          # DB connection & socket config
```

---

## 🧪 How to Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/chatbridge.git
   cd chatbridge
   ```

2. **Set up backend**

   ```bash
   cd server
   npm install
   touch .env
   ```

   Inside `.env`:

   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5001
   ```

   Then run:

   ```bash
   npm start
   ```

3. **Set up frontend**

   ```bash
   cd ../client
   npm install
   npm run dev
   ```

---

## 👩‍💻 Developer
**Shaik Asma**
📧 [LinkedIn](https://www.linkedin.com/in/asma-shaik-47b0ba241) 
