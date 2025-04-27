📚 Booking App

A modern web application that allows users to search, book, and manage reservations seamlessly.
Built with a clean UI/UX, scalable backend, and responsive frontend for a smooth booking experience across all devices.

🚀 Tech Stack

Frontend: React (Next.js) / Vue.js (TBD)
Backend: .NET (Express) / Django (TBD)
Database: PostgreSQL / MongoDB
Design: Figma (UI/UX Design System)
Authentication: JWT (JSON Web Tokens)
Hosting: AWS / Vercel / Netlify (TBD)

👥 Team

Volodymyr — UI/UX Design
Anton — Backend Development
Markiian & Valentyn — Frontend Development

📦 Features

User registration and login
Search and filter listings
Book reservations easily
Manage upcoming and past bookings
Admin panel for managing listings and users
Responsive design (mobile and desktop)
Email notifications (booking confirmations, password resets)
Secure authentication
Calendar integration for availability
User-friendly error handling

🛠️ Setup Instructions

Backend
cd backend
npm install
npm run dev
Frontend
cd frontend
npm install
npm run dev
Environment Variables
Create a .env file in both backend/ and frontend/ with the following:

# Backend
DATABASE_URL=
JWT_SECRET=
EMAIL_SERVICE_API_KEY=

# Frontend
NEXT_PUBLIC_API_URL=

📋 Project Structure

booking-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── app.js
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── utils/
├── design/
│   └── figma/
└── README.md

📈 Future Improvements

Social login (Google, Facebook)
Dark mode support
Multi-language (i18n) support
User favorites / wishlist
Loyalty program integration
Web push notifications

🐞 Known Issues

Double bookings possible when clicking "Book" button rapidly
Booking calendar allows selecting past dates
Booking confirmation email sometimes not sent
Admin dashboard crashes when deleting listings with active bookings
Profile image uploads fail silently on poor connections
Full list of bugs: See Bugs.md
