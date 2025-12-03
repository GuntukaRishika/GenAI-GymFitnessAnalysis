WorkoutApp

A comprehensive fitness application built with a React frontend, Node.js/Express backend, and Python Flask microservices.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

WorkoutApp is a full-stack fitness platform offering personalized workout plans, diet suggestions, and user tracking. It uses modern technologies across frontend, backend, and microservices to deliver a seamless experience.

## Features

### Frontend (React)
- User Authentication (Login / Register)
- Interactive workout plan UI
- Dynamic diet recommendations
- Responsive mobile-friendly design
- Real-time API integration

### Backend (Node.js/Express)
- Secure JWT-based authentication
- CRUD for workouts and diet plans
- MongoDB integration
- User profile management
- Cloudinary file uploads

### Flask Microservice
- ML-based workout recommendations
- Data processing logic
- Additional supporting APIs

## Tech Stack
- **Frontend**: React, Vite
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Auth**: JSON Web Tokens (JWT)
- **File Storage**: Cloudinary
- **Microservices**: Python Flask
- **Styling**: Tailwind / Material UI (TBD)
- **State Management**: Redux / Context API (TBD)

## Prerequisites

Install before starting:
- Node.js (v16+ recommended)
- npm (v8+)
- Python 3.8+
- MongoDB

## Installation

### Clone the Repository
```bash
git clone https://github.com/GuntukaRishika/GenAi-Gym-FitnessAnalysis.git
```

### Install Dependencies

#### Frontend
```bash
cd frontend
npm install
```

#### Backend
```bash
cd backend
npm install
```

#### Flask Microservice
```bash
cd flask-service
pip install -r requirements.txt
```

---

## Environment Variables

### Frontend (.env)
```
VITE_BACKEND_URL=http://localhost:5000
VITE_FLASK_URL=http://localhost:5001
```

### Backend (.env)
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/workoutapp
CORS_ORIGIN=http://localhost:3000

ACCESS_TOKEN_SECRET=your_secret_key
ACCESS_TOKEN_EXPIRY=1d

REFRESH_TOKEN_SECRET=your_refresh_secret
REFRESH_TOKEN_EXPIRY=7d

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_CLOUD_KEY=your_cloudinary_key
CLOUDINARY_CLOUD_SECRET=your_cloudinary_secret

API_KEY=your_api_key
```

## Running the Application

### Development Mode

#### Frontend
```bash
cd frontend
npm run dev
```

#### Backend
```bash
cd backend
npm run dev
```

#### Flask Microservice
```bash
cd flask-service
python app.py
```

### Production Build

#### Frontend
```bash
cd frontend
npm run build
```

#### Backend
```bash
cd backend
npm start
```

## Project Structure
```
WorkoutApp/
│
├── frontend/               # React application
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
├── backend/                # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
└── flask-service/          # Python Flask microservice
    ├── ml_models/
    ├── routes/
    └── app.py
```

## Contributing

1. Fork the repository
2. Create a feature branch
   ```
   git checkout -b feature/MyFeature
   ```
3. Commit your changes
   ```
   git commit -m "Add MyFeature"
   ```
4. Push the branch
   ```
   git push origin feature/MyFeature
   ```
5. Create a Pull Request


### **Project Link**

[https://github.com/GuntukaRishika/GenAI-GymFitnessAnalysis](https://github.com/GuntukaRishika/GenAI-GymFitnessAnalysis)
