# Uber Clone – MERN Stack Ride‑Booking App 🚗

Build a fully functional ride‑sharing app using MongoDB, Express, React, and Node.js, inspired by Uber.

## 🧠 Features
- User authentication (sign up/in)
- Real‑time location tracking with Google Maps
- Ride booking, cancellation, and live updates
- User and driver dashboards
- Trip history storage and display

## 🛠️ Tech Stack
- **Frontend:** React, Google Maps API, Socket.io (optional)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-Time:** Socket.io
- **APIs:** Google Maps for geolocation/directions

## 🚀 Getting Started
1. Clone the repo  
2. `npm install` in both `/client` and `/server`  
3. Copy `.env.example` to `.env` and add your Google API keys + MongoDB URI  
4. `npm run dev` to start both frontend and backend  
5. Access the app at `http://localhost:3000`

## 📈 Features in Detail
- **Authentication:** JWT or session-based login system  
- **Maps & Booking:** Select pick-up/drop-off on map; display driver ETAs  
- **Real-Time Updates:** Socket.io updates driver pinpoint and ride states  
- **Trip History:** MongoDB-stored ride records, viewable via UI

## 🤝 Contributing
Contributions welcome: bug reports, feature requests, pull requests

## 📄 License
MIT License
