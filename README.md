# ה̲מ̲ל̲ו̲נ̲ה (Hameluna) 🐾

**Hameluna** is a full-stack web application designed to improve dog adoption experiences and enhance shelter management. Built as a graduation project by students of Industrial Engineering & Management at Ruppin Academic Center, the app helps create smart matches between adopters and dogs using AI-driven recommendations.

## 🐶 Overview

Hameluna bridges the gap between shelters and adopters by providing:

- A centralized management platform for dog shelters.
- A user-friendly adoption process with smart matching based on personality and preferences.
- Real-time communication and updates between adopters and shelters.

## 🚀 Features

- 🧠 **AI-Based Matching** – Personalized suggestions for adopters based on preferences and dog behavior traits.
- 📋 **Shelter Management System** – Add, update, and manage dogs, their medical history, behavior, and adoption status.
- 📡 **Firebase Realtime Chat** – Secure messaging between shelters and potential adopters.
- 🖼️ **Image Uploads** – Store and manage dog profiles with photo galleries.
- 🔐 **Role-Based Access** – Admin and user permissions, login with authentication and authorization.

## 🛠️ Tech Stack

### 🖥️ Frontend
- React.js
- Firebase Authentication & Realtime Database
- Material UI

### 🔧 Backend
- .NET Core (C#)
- MSSQL Server
- MongoDB (for behavioral data)
- RESTful API architecture

## ⚙️ Installation

> Make sure you have Node.js, .NET Core SDK, and SQL Server installed.

### 1. Clone the repo
```bash
git clone https://github.com/ruppinCgroup54/Hameluna.git
```

### 2. Client Setup
```bash
cd client
npm install
npm start
```

### 3. Server Setup
```bash
cd server
# Update `appsettings.json` with your database connection strings
dotnet restore
dotnet run
```

> Don't forget to set up Firebase credentials and environment variables as required.

## 📷 Screenshots
![Homepage](https://github.com/user-attachments/assets/1e2009c8-c2e4-4b8a-889d-b3c46df251bd)

_(Add screenshots in the `/screenshots` directory to display them here.)_

## 👨‍💻 Authors

- 🧑‍💻 Developed by students of **Ruppin Academic Center** 
- Contributors: [Roni yehoshuan](https://github.com/RoniYehoshua)
                    [Dolev Bash](https://github.com/DolBash)
                    [Ben Shuna](https://github.com/BenShuan)

## 📄 License

This project is for educational use. For other purposes, please contact the repository maintainers.
