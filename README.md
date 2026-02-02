# 🌍 Travelia – Travel Booking Web App

Travelia is a modern travel booking web application built with **React + Firebase**.  
Users can explore trips, view detailed itineraries, book trips, and manage their bookings with authentication support.

---

preview url:https://travel-booking-app-6e665.web.app/trips

---

## 🚀 Features

- 🏠 Beautiful Home page with hero section
- 🧳 Browse Trips with detailed cards
- 🔍 Trip Details page with itinerary, highlights & pricing
- 📝 Booking form with auto-filled user details
- 🔐 Authentication (Email/Password & Google)
- 🔒 Protected routes for bookings
- 📂 My Bookings page (user-specific)
- 📱 Responsive & clean UI
- ⏳ Loading & Error handling

---

## 🛠️ Tech Stack

- **Frontend:** React (Vite)
- **Routing:** React Router DOM
- **State Management:** Context API
- **Authentication:** Firebase Auth
- **Database:** Firebase
- **Styling:** CSS
- **Version Control:** Git & GitHub

---

## 📁 Project Structure

src/
│
├── assets/
├── auth/
│ └── Auth.jsx
│
├── components/
│ ├── pages/
│ │ ├── Trips.jsx
│ │ ├── TripDetail.jsx
│ │ ├── BookingForm.jsx
│ │ └── MyBookings.jsx
│ │
│ └── ui/
│ ├── Navbar.jsx
│ ├── Home.jsx
│ ├── Loading.jsx
│ └── ErrorElement.jsx
│
├── context/
│ └── AuthContext.jsx
│
├── data/
│ └── TripsData.js
│
├── firebase/
│ └── config.js
│
├── routes/
│ ├── Layout.jsx
│ └── ProtectedRoutes.jsx
│
├── App.jsx
├── main.jsx
└── index.css


---

## 🔐 Authentication Flow

- Login / Register using Email & Password
- Login with Google
- Protected routes using `ProtectedRoutes`
- User state handled via `AuthContext`

---

## 📸 Screenshots

- Home Page

<img width="1920" height="990" alt="image" src="https://github.com/user-attachments/assets/83d7ba97-0843-4868-b893-9bbfdc4f776c" />

- Trips Listing

  <img width="1920" height="1769" alt="image" src="https://github.com/user-attachments/assets/93b789f5-9aa3-4c90-84c6-97c05d8898cf" />

- Trip Details

  <img width="1920" height="2307" alt="image" src="https://github.com/user-attachments/assets/a0b3c741-26ad-4dd2-82c1-f8506296c8f4" />

- Booking Form

  <img width="1920" height="912" alt="image" src="https://github.com/user-attachments/assets/0b5d0c9d-db68-479f-9ef8-9519a018c7b7" />

- Login Page

<img width="1920" height="982" alt="image" src="https://github.com/user-attachments/assets/d87769c7-4d88-4f75-8a0f-3131c005fdad" />


---

## ⚙️ Installation & Setup

1. Clone the repository

```bash

git clone https://github.com/your-username/travelia.git

2. Install dependencies

npm install

3. Start the development server

npm run dev

