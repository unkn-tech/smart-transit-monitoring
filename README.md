<img width="1920" height="1080" alt="Screenshot 2026-05-28 191413" src="https://github.com/user-attachments/assets/7ed3b7e7-a1e1-4dfb-afe2-ba6c279660b6" /><img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5ac93ae-160c-4b97-8031-8a52753d2772" /># 🚌 SmartTransit — Smart Transit Monitoring System for Bengaluru Bus Routes

> An intelligent real-time public transportation monitoring system designed to improve the daily commute experience across Bengaluru bus routes.

---

## 📌 Overview

**SmartTransit** is a full-stack smart public transit monitoring platform built as a major academic project. The system simulates real-time bus tracking, crowd monitoring, traffic-aware ETA prediction, and route analytics for Bengaluru city buses.

The project aims to solve common commuter problems such as:

* ⏳ Unpredictable bus arrival times
* 🧍 Overcrowded buses
* 🚦 Traffic-related delays
* 📍 Lack of real-time transit visibility

Using a modern web-based dashboard and live map interface, SmartTransit provides commuters and transport authorities with actionable transit insights in real time.

---

# 🚀 Key Features

### 📍 Real-Time GPS Bus Simulation

* Simulates live movement of buses across **4 major Bengaluru routes**
* Dynamic location updates using a custom Node.js simulation engine

### ⏱️ Intelligent ETA Prediction

* Calculates Estimated Time of Arrival (ETA)
* ETA adapts automatically based on:

  * 🟢 Light Traffic
  * 🟡 Moderate Traffic
  * 🔴 Heavy Traffic

### 👥 Smart Crowd Estimation

* Monitors passenger capacity
* Classifies buses into:

  * Low Crowd
  * Medium Crowd
  * High Crowd

### 🤖 Smart Bus Recommendation

* Suggests the best bus based on:

  * Lowest ETA
  * Comfortable crowd level
  * Route availability

### 🗺️ Live Interactive Map

* Visualizes:

  * Bus locations
  * Routes
  * Stops
* Powered using **React-Leaflet + OpenStreetMap**

### 📊 Authority Analytics Dashboard

* Displays:

  * Route-wise passenger load
  * Delay statistics
  * Traffic impact trends
  * Operational insights

---

# 🛠️ Tech Stack

| Category             | Technologies                                          |
| -------------------- | ----------------------------------------------------- |
| 🎨 Frontend          | React, Vite, React Router, React-Leaflet, Vanilla CSS |
| ⚙️ Backend           | Node.js, Express.js                                   |
| 🗄️ Database         | SQLite                                                |
| 🔄 Simulation Engine | Custom Node.js Interval-Based Engine                  |
| 🗺️ Maps             | Leaflet + OpenStreetMap                               |

---

# 🏗️ System Architecture

The application follows a **Full-Stack Client-Server Architecture**.

### 🔹 Backend

* Acts as an independent REST API layer
* Handles:

  * Bus simulation
  * ETA calculations
  * Crowd estimation
  * Analytics generation
* Stores route and transit data using SQLite

### 🔹 Frontend

* Built as a **Single Page Application (SPA)** using React + Vite
* Fetches real-time data from backend every **3 seconds**
* Displays:

  * Live dashboard
  * Interactive maps
  * Transit analytics

---

# 📂 Project Structure

```bash
SmartTransit/
│
├── frontend/        # React + Vite Frontend
├── backend/         # Node + Express Backend
├── database/        # SQLite Database Files
├── public/          # Static Assets
└── README.md
```

---

# ⚡ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/smarttransit.git
cd smarttransit
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

This installs dependencies for both frontend and backend.

---

## 3️⃣ Start the Application

```bash
npm start
```

This command uses **concurrently** to run:

* 🚀 Node.js Backend Server
* ⚡ Vite Development Server

---

## 4️⃣ Open in Browser

```bash
http://localhost:5173
```

---

# 📸 Screenshots

## 🏠 Dashboard View
<img width="1920" height="1080" alt="Screenshot 2026-05-28 191329" src="https://github.com/user-attachments/assets/75b598de-98ae-445e-86d5-fd3d6bee10cd" />
<img width="1920" height="1080" alt="Screenshot 2026-05-28 191336" src="https://github.com/user-attachments/assets/c692a984-b815-460e-af25-4cbd1d67b2a3" />

## 📊 Analytics Dashboard
<img width="1920" height="1080" alt="Screenshot 2026-05-28 191413" src="https://github.com/user-attachments/assets/f93d5903-6ec7-43bd-a214-a3a593afc4c4" />
<img width="1920" height="1080" alt="Screenshot 2026-05-28 191419" src="https://github.com/user-attachments/assets/ef248e5b-31bc-444a-9428-8846ed6132f1" />


---

# 🎯 Project Objectives

* Improve commuter convenience using real-time transit information
* Reduce uncertainty in bus arrival timings
* Demonstrate practical full-stack development skills
* Simulate smart-city transportation analytics

---

# 🔮 Future Enhancements

### 📡 Real GPS Integration

Connect with actual GPS devices installed in buses.

### 🤖 AI-Based Predictive ETA

Use Machine Learning models to predict delays using:

* Historical traffic data
* Weather conditions
* Peak-hour congestion

### 📱 Mobile Application

Develop Android/iOS apps for commuters.

### ☁️ Cloud Deployment

Deploy using:

* AWS
* Render
* Railway
* Docker + Kubernetes

### 🔔 Smart Notifications

* Bus arrival alerts
* Delay notifications
* Crowd warnings

---

# 👨‍💻 Learning Outcomes

This project demonstrates:

* Full-Stack Web Development
* REST API Design
* Real-Time Data Simulation
* Map Integration
* Database Management
* Dashboard & Analytics Design

---

# 📜 License

This project is developed for academic and educational purposes.

---

# ❤️ Acknowledgements

* Bengaluru Metropolitan Transport Corporation (BMTC) inspiration
* OpenStreetMap
* Leaflet.js
* React Community

---

# 🌟 SmartTransit

> “Making Bengaluru Bus Travel Smarter, Safer, and More Predictable.” 🚍
