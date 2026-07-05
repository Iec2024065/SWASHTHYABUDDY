# SwashthyaBuddy – College Health Center Web Application

SwashthyaBuddy is a full-stack web application designed for college health centers, enabling students, doctors, and administrators to manage appointments, health records, and communication efficiently. The project features a modern React frontend (Material-UI), a secure Node.js/Express backend, and a MongoDB Atlas database.

🌐 **Live Website**: [https://swashthyabuddy.vercel.app](https://swashthyabuddy.vercel.app)

---

## Features

- **User Authentication**: Secure JWT-based login/signup for students, doctors, and admins
- **Role-Based Access**: Admin, doctor, and patient dashboards with tailored features
- **Appointment Management**: Book, view, and manage appointments
- **Doctor & Patient Profiles**: View and edit personal and professional information
- **Chat & Notifications**: Real-time chat and notification system
- **Symptom Checker**: AI-powered symptom analysis tool
- **Activity Logs & Analytics**: Admin tools for monitoring and reporting
- **Responsive UI**: Modern, accessible design using Material-UI with dark/light mode

---

## Tech Stack

- **Frontend**: React, Material-UI (MUI), Axios, Socket.io-client
- **Backend**: Node.js, Express, JWT, Mongoose, Socket.io
- **Database**: MongoDB Atlas
- **Deployment**: Vercel (frontend), Render (backend)

---

## Project Structure

```
SWASHTHYABUDDY/
  backend/    # Express API, controllers, models, routes, middleware
  frontend/   # React app, components, pages, contexts, services
```

---

## Getting Started (Development)

### Prerequisites
- Node.js (v16+ recommended)
- MongoDB Atlas account (or local MongoDB for dev)

### 1. Clone the Repository
```sh
git clone https://github.com/Iec2024065/SWASHTHYABUDDY.git
cd SWASHTHYABUDDY
```

### 2. Backend Setup
```sh
cd backend
npm install
# Create .env file (see .env.example)
# MONGODB_URI=your_mongodb_atlas_uri
# JWT_SECRET=your_jwt_secret
# FRONTEND_URL=http://localhost:3000
npm run dev
```

### 3. Frontend Setup
```sh
cd ../frontend
npm install
# REACT_APP_API_URL=http://localhost:5001/api
npm start
```

---

## Deployment

- **Frontend**: Deployed on [Vercel](https://vercel.com) — [https://swashthyabuddy.vercel.app](https://swashthyabuddy.vercel.app)
- **Backend**: Deployed on [Render](https://render.com) — [https://swashthyabuddy.onrender.com](https://swashthyabuddy.onrender.com)

---

## API Overview

- `/api/auth/login` – User login
- `/api/auth/signup` – User registration
- `/api/appointments` – Appointment management
- `/api/profile` – User profile endpoints
- `/api/chat` – Real-time chat
- `/api/analytics` – Admin analytics

---

## License

MIT

---

## Contributors

- [Singirikonda Navaneeth](https://github.com/Iec2024065)

---

## Acknowledgements

- Material-UI
- Vercel
- Render
- MongoDB Atlas
