# 📡 VCallPe – Real-Time Video Conferencing Platform

**VCallPe** is a full-stack video conferencing application designed to demonstrate real-world applications of **computer networking** concepts such as **peer-to-peer communication**, **NAT traversal**, **signaling**, and **real-time media streaming**. Built with the **MERN stack**, the app utilizes **WebRTC** for low-latency audio/video transmission and **Socket.IO** for signaling and chat.

This project showcases how front-end and back-end systems can coordinate to establish secure and efficient real-time communication, making it ideal for academic or professional portfolios focused on **network protocols**, **distributed communication**, or **network-aware applications**.


---

## 🧠 Key Networking Concepts

- **WebRTC (Web Real-Time Communication)**  
  Enables browser-to-browser media streaming using peer-to-peer connections. Supports ICE (Interactive Connectivity Establishment) to traverse NAT/firewalls and connect over STUN/TURN servers.

- **ICE (Interactive Connectivity Establishment)**  
  Helps find the best path for direct communication between peers, even if they are behind NAT devices.

- **STUN/TURN Servers**  
  Used for NAT traversal. STUN helps clients discover their public address, while TURN relays data if direct connection fails.

- **Socket.IO over WebSockets**  
  Used for real-time, event-based signaling and chat. Supports persistent TCP-based communication with fallback handling.

- **Secure Authentication**  
  Login & registration via hashed passwords using **bcrypt**. Sessions managed via JWT tokens (locally stored).

- **RESTful APIs over HTTP**  
  Implements secure APIs using Express.js to handle user actions, showcasing traditional client-server communication.

- **Room-Based Signaling Architecture**  
  Users can create and join custom rooms. Each room manages media signaling independently using sockets.

---

## 🛠 Tech Stack

| Layer       | Technology                           |
|-------------|---------------------------------------|
| Frontend    | React, Material UI, WebRTC, Axios     |
| Backend     | Node.js, Express.js, Socket.IO, Bcrypt|
| Database    | MongoDB (via Mongoose ODM)            |
| Protocols   | HTTP, WebSockets, ICE, STUN/TURN      |

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18+
- MongoDB Atlas connection string or local MongoDB instance
- Two terminals for running frontend and backend

---

### 1. Clone the Repository

```bash
git clone https://github.com/sanjaydsetty/VCallPe.git
cd vcallpe
