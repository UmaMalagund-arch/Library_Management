# 📚 Library Management System

A lightweight **Library Management System** web app built using **HTML, CSS, and JavaScript**, containerized with **Docker** and served through **Nginx**.  
Easily add, view, and delete books with a clean and responsive dark-themed interface.

---

## 🚀 Features

- ⚡ **Lightweight Nginx-based Docker container**
- 🐳 **Simple setup using Docker Compose**
- 🖤 **Responsive dark theme design**
- 🔄 **Easy local testing with port mapping**
- 💾 **LocalStorage support for persistent data**

---

## 🧱 Project Structure
library-management-system/
│
├── Dockerfile
├── docker-compose.yml
├── index.html
├── style.css
├── script.js
└── README.md


---

## ⚙️ Installation & Setup

### Step 1: Install Docker & Docker Compose
```bash
sudo apt update
sudo apt install docker.io -y
sudo apt install docker-compose -y

Step 2: Build & Run
docker-compose up --build

Step 3: Access App

👉 Open your browser and go to:
http://localhost:8000

📦 Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Containerization	Docker
Web Server	Nginx
Orchestration	Docker Compose

