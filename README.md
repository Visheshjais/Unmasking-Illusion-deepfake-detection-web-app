# 🎭 Unmasking Illusion — Deepfake Detection Web App

![GitHub repo size](https://img.shields.io/github/repo-size/Visheshjais/Unmasking-Illusion-deepfake-detection-web-app?color=6C63FF)
![GitHub last commit](https://img.shields.io/github/last-commit/Visheshjais/Unmasking-Illusion-deepfake-detection-web-app?color=00C9A7)
![GitHub stars](https://img.shields.io/github/stars/Visheshjais/Unmasking-Illusion-deepfake-detection-web-app?style=social)

> A full-stack web application that detects deepfake images and videos using AI-powered analysis — combining modern web development with real-world problem-solving.

---

## 🌐 Live Demo

🔗 **[View Live →](https://your-live-link.vercel.app)**

---

## 📸 Screenshots

| Home Page | Detection Result |
|---|---|
| ![Home](./screenshots/home.png) | ![Result](./screenshots/result.png) |

---

## 🧠 What is a Deepfake?

Deepfakes are AI-generated media where a person's likeness is replaced with someone else's. This project aims to **detect such manipulated content** to promote digital trust and media authenticity.

---

## ✨ Features

- 🔍 **Deepfake Detection** — Upload an image or video and get real-time AI analysis
- 📊 **Confidence Score** — Shows probability of content being real or fake
- 🔐 **User Authentication** — Secure login & signup with JWT
- 📱 **Fully Responsive** — Works seamlessly on mobile, tablet & desktop
- ⚡ **Fast & Clean UI** — Built with React & Tailwind CSS for smooth UX
- 🗂️ **Detection History** — View past analysis results (if logged in)

---

## 🛠️ Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

**AI / Detection**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=fastapi&logoColor=white)

---

## 🏗️ Project Architecture
```
Unmasking-Illusion/
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Home, Upload, Results, Auth
│   │   ├── context/         # Auth context (JWT)
│   │   └── App.jsx
├── server/                  # Node.js + Express backend
│   ├── routes/              # API routes
│   ├── models/              # MongoDB schemas
│   ├── middleware/          # JWT auth middleware
│   └── index.js
├── model/                   # AI detection model/API
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- npm or yarn

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/Visheshjais/Unmasking-Illusion-deepfake-detection-web-app.git
cd Unmasking-Illusion-deepfake-detection-web-app
```

**2. Install frontend dependencies**
```bash
cd client
npm install
```

**3. Install backend dependencies**
```bash
cd ../server
npm install
```

**4. Set up environment variables**

Create a `.env` file in the `/server` directory:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

**5. Run the application**

Backend:
```bash
cd server
npm run dev
```

Frontend:
```bash
cd client
npm run dev
```

**6. Open in browser**
```
http://localhost:5173
```

---

## 🔌 API Endpoints

| Method | Endpoint | Description | Auth |
|---|---|---|---|
| POST | `/api/auth/register` | Register new user | ❌ |
| POST | `/api/auth/login` | Login user | ❌ |
| POST | `/api/detect` | Upload & detect deepfake | ✅ |
| GET | `/api/history` | Get detection history | ✅ |

---

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

---

## 👨‍💻 Authors & Contributors

### Vishesh Jaiswal
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishesh-j-a085b3236/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Visheshjais)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://visheshjaiswalportfolio.vercel.app/)

### Anuroop Srivastava
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnuroopSrivastava)

---

## 🤝 Contributing

This project was built as a college project by **Vishesh Jaiswal** and **Anuroop Srivastava** at
**Jaypee University of Information Technology (JUIT)**.

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/Visheshjais/Unmasking-Illusion-deepfake-detection-web-app/issues).

1. Fork the repository
2. Create a new branch `git checkout -b feature/your-feature`
3. Commit your changes `git commit -m "add your feature"`
4. Push to the branch `git push origin feature/your-feature`
5. Open a Pull Request

---

<p align="center">⭐ Star this repo if you found it helpful!</p>
<p align="center">Built with ❤️ at JUIT by Vishesh Jaiswal & Anuroop Srivastava</p>
```


