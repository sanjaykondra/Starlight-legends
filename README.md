# Starlight-legends

starlight-legends/
│
├── backend/
│   ├── package.json
│   ├── server.js
│   ├── firebase.js
│   └── .env
│
├── frontend/
│   ├── package.json
│   ├── public/
│   │   └── index.html
│   └── src/
│       ├── index.js
│       ├── App.js
│       ├── components/
│       │   ├── Navbar.js
│       │   ├── Trailer.js
│       │   ├── Leaderboard.js
│       │   ├── Multiplayer.js
│       │   └── Badges.js
│       └── styles/
│           └── main.css
│
└── README.md
```

---

# ==========================
# ⭐ BACKEND FULL CODE ⭐
# ==========================

## 📄 backend/package.json
```json
{
  "name": "starlight-backend",
  "version": "1.0.0",
  "main": "server.js",
  "type": "module",
  "dependencies": {
    "express": "^4.18.2",
    "firebase-admin": "^12.0.0",
    "socket.io": "^4.7.5",
    "cors": "^2.8.5"
  },
  "scripts": {
    "start": "node server.js"
  }
}
