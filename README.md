# 🚗 AeroRide – Next-Gen Ride Hailing Platform

Welcome to **AeroRide**, a full-stack, real-time ride-hailing application inspired by the best of Uber’s user experience and technology. This project demonstrates modern web engineering, scalable backend architecture, and seamless real-time communication between riders and captains.

---

## 🌟 Why AeroRide Stands Out

- **Real-Time Ride Matching:** Instantly connect riders with nearby captains using live location tracking and socket-powered notifications.
- **Interactive Maps:** Google Maps integration for live tracking, pickup/destination suggestions, and route visualization.
- **OTP-Based Ride Security:** Each ride is protected with a unique OTP for safe and verified ride starts.
- **Captain & User Flows:** Separate, secure authentication and dashboards for both captains and users.
- **Modern UI/UX:** Built with React, TailwindCSS, and GSAP for smooth, mobile-friendly animations and transitions.
- **Robust Backend:** Node.js, Express, MongoDB, and Socket.io for scalable, secure, and fast API responses.
- **Extensible Architecture:** Easily add new features, payment integrations, or analytics.

---

## 🚀 Features

- **User Registration & Login:** Secure JWT authentication, password hashing, and token blacklisting.
- **Captain Onboarding:** Register vehicles, manage status, and receive ride requests in real time.
- **Ride Creation & Fare Calculation:** Dynamic fare estimates based on distance and time using Google APIs.
- **Live Ride Tracking:** Both users and captains see live locations and ride status updates.
- **Ride Confirmation & Completion:** OTP verification for ride start, and secure ride completion flow.
- **Socket.io Notifications:** Real-time updates for ride requests, confirmations, and completions.
- **Autocomplete Location Search:** Google Places API for fast, accurate address suggestions.

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite, TailwindCSS, GSAP, @react-google-maps/api
- **Backend:** Node.js, Express, MongoDB, Socket.io
- **APIs:** Google Maps, Google Places
- **Authentication:** JWT, bcrypt, token blacklisting
- **Dev Tools:** ESLint, PostCSS, Vite

---

## 📦 Project Structure

```
uber-video/
├── Backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── middlewares/
│   ├── db/
│   ├── app.js
│   └── socket.js
├── frontend/
│   ├── src/
│   ├── public/
│   ├── index.html
│   ├── tailwind.config.js
│   └── vite.config.js
└── .gitignore
```

---

## 🏁 Getting Started

1. **Clone the repo:**
   ```sh
   git clone https://github.com/yourusername/uber-video.git
   cd uber-video
   ```

2. **Setup Backend:**
   - Add your MongoDB and Google Maps API keys to `Backend/.env`.
   - Install dependencies:
     ```sh
     cd Backend
     npm install
     npm start
     ```

3. **Setup Frontend:**
   - Add your Google Maps API key to `frontend/.env`.
   - Install dependencies:
     ```sh
     cd ../frontend
     npm install
     npm run dev
     ```

4. **Access the app:**
   - Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🤝 Contributing

Pull requests, issues, and feature suggestions are welcome! Let’s build the future of mobility together.

---


