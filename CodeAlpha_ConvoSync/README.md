# 🚀 ConvoSync

> A modern real-time video conferencing and collaboration platform built with React, TypeScript, Node.js, Socket.IO, and WebRTC.

ConvoSync enables users to create secure meeting rooms, communicate through high-quality video and audio, collaborate using a real-time whiteboard, and manage meetings through a clean, responsive interface.

---

## 📌 Overview

ConvoSync is designed to provide a seamless online collaboration experience. Users can create an account, join or create meeting rooms, communicate through live video and audio, and collaborate using an interactive whiteboard.

The project combines modern frontend technologies with a Node.js backend, MongoDB authentication, Socket.IO real-time communication, and WebRTC peer-to-peer media streaming.

---

# ✨ Features

### 🔐 Authentication
- User Registration
- Secure Login
- JWT Authentication
- Password Hashing using bcrypt

### 🎥 Video Conferencing
- Create meeting rooms
- Join existing rooms
- Real-time peer-to-peer video calls
- Audio controls
- Video controls
- Screen sharing

### 🎨 Collaborative Whiteboard
- Real-time drawing
- Multi-user collaboration
- Color selection
- Live synchronization

### 💬 Collaboration
- Room-based communication
- Participant management
- Live meeting experience

### 🎨 UI Features
- Dark Theme
- Light Theme
- Glass Theme
- Responsive Design
- Smooth Animations (Framer Motion)

---

# 🛠 Tech Stack

## Frontend

- React 19
- TypeScript
- Vite
- React Router
- Tailwind CSS
- Framer Motion
- Socket.IO Client
- Simple Peer (WebRTC)
- Lucide React Icons

## Backend

- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- Socket.IO
- JWT Authentication
- bcrypt

---

# 📂 Project Structure

```
ConvoSync
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── ThemeContext.tsx
│   ├── socket.ts
│   └── App.tsx
│
├── server/
│   ├── models/
│   ├── server.ts
│   └── package.json
│
├── package.json
└── README.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/Apoorv-Gaurav/CodeAlpha_ConvoSync.git

cd CodeAlpha_ConvoSync
```

---

## Install Frontend

```bash
npm install
```

---

## Install Backend

```bash
cd server

npm install
```

---

# 🔑 Environment Variables

## Frontend (.env)

```env
VITE_API_URL=http://localhost:5000
```

---

## Backend (.env)

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

---

# ▶ Running the Project

## Start Backend

```bash
cd server

npm run dev
```

---

## Start Frontend

```bash
npm run dev
```

Open

```
http://localhost:5173
```

---

# 📸 Screenshots

Add screenshots here.

Example:

```
screenshots/

├── login.png
├── dashboard.png
├── room.png
├── whiteboard.png
```

---

# 🌟 Core Functionalities

- Secure Authentication
- JWT Login Sessions
- Video Calling
- Audio Controls
- Camera Controls
- Screen Sharing
- Collaborative Whiteboard
- Theme Switching
- Responsive Interface
- MongoDB User Storage
- Real-time Socket Communication

---

# 🔒 Security

- Passwords encrypted using bcrypt
- JWT-based authentication
- MongoDB secure storage
- Protected API endpoints

---

# 🚀 Future Improvements

- Meeting Chat
- File Sharing
- Meeting Recording
- Raise Hand Feature
- Waiting Room
- User Profiles
- Meeting History
- Calendar Integration
- Notifications
- Admin Controls

---

# 👨‍💻 Author

**Apoorv Gaurav**

GitHub:
https://github.com/Apoorv-Gaurav

---

# 📄 License

This project was developed as part of the **CodeAlpha Internship Program** and is intended for educational and portfolio purposes.

---

## ⭐ If you found this project useful, consider giving it a Star!
