# 🎥 EchoMeet - Video Meeting Platform

EchoMeet is a full-stack video meeting application where users can create or join meeting rooms and connect with others in real time. The main goal of this project was to understand how real-time communication works and how to build a complete web application from frontend to backend.

While building this project, I learned how to connect multiple users in the same room, manage live communication using Socket.IO, and work with authentication, databases, and REST APIs.

---

##  Features

* User registration and login
* Create a new meeting room
* Join an existing meeting using a Room ID
* Real-time video calling
* Audio mute and unmute
* Camera on and off
* Screen sharing
* Live chat during meetings
* Multiple users can join the same meeting
* Responsive design for different screen sizes

---

## 🛠 Tech Stack

### Frontend

* React.js
* Material UI
* React Router
* Axios
* Socket.IO Client

### Backend

* Node.js
* Express.js
* Socket.IO
* MongoDB
* Mongoose
* Bcrypt
* JWT Authentication

---

## 📂 Project Structure

```text
EchoMeet-video-call
│
├── frontend
│   ├── public
│   ├── src
│   └── package.json
│
├── backend
│   ├── src
│   ├── package.json
│   └── .env
│
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aman9621/Echomeet-video-call.git
```

Go inside the project folder.

```bash
cd Echomeet-video-call
```

---

### 2. Install dependencies

Backend

```bash
cd backend
npm install
```

Frontend

```bash
cd ../frontend
npm install
```

---

### 3. Add Environment Variables

Create a `.env` file inside the **backend** folder.

Example:

```env
PORT=8000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

---

### 4. Start the backend

```bash
npm run dev
```

---

### 5. Start the frontend

```bash
cd ../frontend
npm start
```

The application will open at:

```
http://localhost:3000
```

---

## 💭 Why I Built This Project

I wanted to build a project that helped me understand real-time applications. Most web applications work by sending requests and waiting for responses, but video meeting apps are different because everything needs to update instantly.

This project gave me practical experience with Socket.IO, managing meeting rooms, handling multiple users, and connecting the frontend with the backend.

---

## 📚 What I Learned

While working on EchoMeet, I learned:

* How Socket.IO works for real-time communication
* How to create and manage meeting rooms
* Connecting React with an Express backend
* Working with MongoDB using Mongoose
* User authentication and password encryption
* Building REST APIs
* Managing project structure in a full-stack application
* Handling client and server communication

---

## 🔮 Future Improvements

There are still many features I would like to add in the future.

* Meeting recording
* Waiting room before joining
* Meeting scheduling
* File sharing
* Emoji reactions
* Virtual backgrounds
* Better host controls
* Meeting history
* Notifications

---

## 🤝 Contributing

If you have any ideas or find a bug, feel free to open an issue or create a pull request. Suggestions are always welcome.

---

## 👨‍💻 Author

**Aman Kumar**

GitHub:
https://github.com/aman9621

LinkedIn:
https://www.linkedin.com/in/aman9601

LeetCode:
https://leetcode.com/u/Aman9934/

Email:
[kumaraman29276@gmail.com](mailto:kumaraman29276@gmail.com)

Resume:
https://drive.google.com/file/d/1RTTN7FbcsFANWmV2VEemt5hpf_BbDSYQ/view?usp=sharing

---

## ⭐ If you like this project

If you found this project helpful or interesting, please consider giving it a ⭐ on GitHub. It really motivates me to build more projects and keep learning.

Thank you for visiting my repository!
