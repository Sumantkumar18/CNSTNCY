# CNSTNCY — Video Calling Platform 🎥

![CNSTNCY Banner](https://cnstncweb.onrender.com)

> **Connect with your loved ones. Cover a distance by CNSTNCY Video Call.**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-cnstncweb.onrender.com-orange?style=for-the-badge)](https://cnstncweb.onrender.com)
[![GitHub](https://img.shields.io/badge/GitHub-Sumantkumar18%2FCNSTNCY-black?style=for-the-badge&logo=github)](https://github.com/Sumantkumar18/CNSTNCY)

---

## 📸 Preview

![CNSTNCY Homepage](https://cnstncweb.onrender.com)

> 🎬 **[Watch Demo Video](https://github.com/Sumantkumar18/CNSTNCY)** — See CNSTNCY in action!

---

## ✨ Features

- 🎥 **Real-time Video Calling** — Crystal clear peer-to-peer video calls
- 🎙️ **Audio Controls** — Mute/unmute microphone on the fly
- 🖥️ **Screen Sharing** — Share your screen with participants
- 💬 **In-call Chat** — Send messages without leaving the call
- 🔐 **User Authentication** — Secure register & login system
- 📜 **Meeting History** — Track all your past meetings
- 👥 **Multi-participant** — Multiple users can join the same room
- 🌐 **Guest Access** — Join as guest without registration

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MUI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=mui&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

### Deployment
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

---

## 🚀 Live Demo

🌐 **[https://cnstncweb.onrender.com](https://cnstncweb.onrender.com)**

> ⚠️ The backend is hosted on Render's free tier — it may take **30-50 seconds** to wake up on first load.

---

## 📦 Installation & Setup

### Prerequisites
- Node.js v18+
- MongoDB Atlas account

### Clone the repo
```bash
git clone https://github.com/Sumantkumar18/CNSTNCY.git
cd CNSTNCY
```

### Backend Setup
```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:
```env
MONGO_URI=your_mongodb_connection_string
PORT=8000
```

Start the backend:
```bash
node src/app.js
```

### Frontend Setup
```bash
cd frontend
npm install --legacy-peer-deps
npm start
```

Update `frontend/src/environment.js`:
```js
let IS_PROD = false;
const server = IS_PROD ?
    "https://cnstncweb.onrender.com" :
    "http://localhost:8000"
export default server;
```

---

## 📁 Project Structure

```
CNSTNCY/
├── frontend/                 # React application
│   ├── src/
│   │   ├── pages/            # Landing, Auth, Home, VideoMeet, History
│   │   ├── contexts/         # AuthContext
│   │   ├── styles/           # CSS Modules
│   │   └── environment.js    # API URL config
│   └── public/
├── backend/                  # Node.js + Express server
│   └── src/
│       ├── controllers/      # User & Socket controllers
│       ├── models/           # MongoDB models
│       └── routes/           # API routes
```

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/v1/users/register` | Register a new user |
| POST | `/api/v1/users/login` | Login and get token |
| GET | `/api/v1/users/get_all_activity` | Get meeting history |
| POST | `/api/v1/users/add_to_activity` | Save meeting to history |

---

## 🤝 Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Sumant Kumar**
- GitHub: [@Sumantkumar18](https://github.com/Sumantkumar18)
- Live Project: [cnstncweb.onrender.com](https://cnstncweb.onrender.com)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ by Sumant Kumar</p>
