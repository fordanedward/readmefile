# 🎯 Gordon College Capture the Flag (GC Capture)

![GC Banner](https://via.placeholder.com/800x200.png?text=Gordon+College+Capture+the+Flag)

---

## 🏁 What is GC Capture?

**Gordon College Capture the Flag (GC Capture)** is a cybersecurity challenge platform designed for Gordon College students to practice, compete, and enhance their cybersecurity skills through real-world problem-solving.

---

## ✨ Features

- 🕵️‍♂️ Realistic Cybersecurity Challenges  
- 🧩 Various Categories: Web, Forensics, Cryptography, and more  
- 🎉 Competitive and Educational Environment  
- 🏆 Leaderboard and Achievements  
- 💡 Beginner-Friendly & Advanced Levels  

---

## 📸 Screenshots

| Challenge Preview                           | Leaderboard Example                          |
|---------------------------------------------|----------------------------------------------|
| ![Challenges](https://via.placeholder.com/400x200.png?text=Challenge+Preview) | ![Leaderboard](https://via.placeholder.com/400x200.png?text=Leaderboard) |

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/gc-capture.git
cd gc-capture
npm install
npm run dev


# 📘 GC Capture (Gordon College CTF) – README Guide

## 📋 Table of Contents

- [🧭 Introduction](#-introduction)
- [🧱 Structure of a README.md](#-structure-of-a-readmemd)
- [🔖 Title and Description](#-title-and-description)
- [🛠️ Installation](#️-installation)
- [🚀 Usage](#-usage)
  - [Public/User Routes](#publicuser-routes)
  - [Admin Routes](#admin-routes)
- [🤝 Contributing](#-contributing)

---

## 🧭 Introduction

Welcome to **GC Capture** – a cybersecurity challenge platform for Gordon College students! This project provides a hands-on space to solve CTF (Capture the Flag) challenges, monitor progress, and develop cybersecurity skills in a competitive environment.

This README not only describes GC Capture but also serves as a guide on writing effective README files.

---

## 🧱 Structure of a README.md

### 🔖 Title and Description

```
# 🚩🎯 GC Capture / Gordon College CTF

Welcome to GC Capture! Where future defenders train, compete, and dominate.

Gordon College CTF is a cybersecurity challenge platform designed to help students **train, compete, and grow** through solving realistic CTF challenges in a structured environment.


🛠️ Installation
1. Clone and set up the project:

```bash
# Clone the repository
git clone https://github.com/yourusername/gc-capture.git
cd gc-capture
```
2. Install dependencies:

```bash
# Install base dependencies defined in package.json
npm install

# Install react-icons – used for rendering icons in the UI
npm install react-icons

# Install Recharts – for drawing interactive charts in statistics pages
npm install recharts

# Install tw-animate-css – to easily add utility animation classes using Tailwind-compatible naming
npm install tw-animate-css

# Install Chart.js and react-chartjs-2 – for additional visualizations and dashboard analytics
npm install chart.js react-chartjs-2
```

3. Start the local development server:

```bash
npm run dev
```

🚀 Usage
Once the app is running, users and admins can access the following routes:

Public/User Routes:
```bash
/login – Login page for users
/ – Hero landing page
/profile – User profile page
/user-statistics – User performance and statistics page
/challenges – Page where users can view and solve CTF challenges
```

Admin Routes:
```bash
/admin/dashboard – Admin dashboard overview
/admin/challenges – Manage and organize challenges
/admin/specific_challenge – View or edit specific challenge details
/admin/overall_events – View a list of all events
/admin/events – Manage events; includes modal for adding new events
/admin/student – Manage student participants and access controls
```

## 🤝 Contributing

We welcome contributions from everyone! If you want to help improve GC Capture, follow these steps:

1. Fork this repository
2. Create a new branch for your feature or fix
3. Commit your changes with clear messages
4. Push to your fork and submit a Pull Request

Please follow the existing code style and conventions. If you have questions, feel free to open an issue or ask for guidance. Thank you for helping make this project better!

## Profile Page

The profile page allows users to:

1. View and update their profile information
2. Upload a profile picture
3. Change their password
4. Navigate to their statistics page

### API Integration

The profile page connects to the following API endpoints:
```bash
- `GET /users/profile` - Get the current user's profile data
- `PUT /users/profile` - Update the user's profile data
- `POST /users/profile/picture` - Upload a profile picture
- `POST /users/change-password` - Change the user's password
```
### Implementation Details
```bash
- Uses a dedicated `useProfilePage` hook for API interactions
- Handles loading states and errors
- Provides user feedback through toast notifications
- Supports both absolute and relative profile picture URLs
```

## 🛠️ Built With
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge\&logo=vite\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge\&logo=react-router\&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-F5788D?style=for-the-badge\&logo=chartdotjs\&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=for-the-badge\&logo=recharts\&logoColor=white)
![Headless UI](https://img.shields.io/badge/HeadlessUI-000000?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![Lucide](https://img.shields.io/badge/Lucide-000000?style=for-the-badge\&logo=lucide\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)

---
