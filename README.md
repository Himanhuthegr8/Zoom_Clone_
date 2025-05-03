# 📹 Zoom Clone

A simple video conferencing web application built with WebRTC, Node.js, and Socket.io — mimicking core functionalities of Zoom like real-time video calls, chat, and room creation.

---

## 📖 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 Overview

This project is a clone of Zoom's basic video conferencing functionalities. Users can create or join virtual rooms, enabling peer-to-peer video calls and messaging in real time. It's a lightweight and educational example of implementing WebRTC with a Node.js and Socket.io backend.

---

## ✨ Features

- 🔐 Unique room generation for video calls
- 🎥 Real-time video and audio streaming with WebRTC
- 💬 Real-time text chat within rooms
- 🌐 Peer-to-peer connections via WebRTC and PeerJS
- 📡 WebSocket-based signaling with Socket.io
- 📱 Responsive design for various screen sizes

---

## 📂 Project Structure

```plaintext
Zoom_Clone_/
├── node_modules/              # Project dependencies
├── public/
│   ├── js/
│   │   └── script.js          # Frontend JS for video call logic
│   ├── style.css              # Stylesheet for the app
│   └── index.html             # Main HTML file
├── views/
│   └── room.ejs               # EJS template for room pages
├── package.json               # Project metadata and scripts
├── server.js                  # Node.js + Express server file
└── README.md                  # Project documentation
