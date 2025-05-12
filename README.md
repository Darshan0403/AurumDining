# AurumDining

AurumDining is a full-scale restaurant management system that offers separate features for customers and administrators. Built using the MERN stack (MongoDB, Express.js, React, Node.js), it supports real-time table reservations, food ordering, and complete admin control over orders and bookings.

---

## Features

### Customer Features
- View menu and order food for takeaway
- Reserve tables based on date and available time slots
- Reserve tables with a pre-selected food order
- Responsive, user-friendly interface

### Admin Features
- Secure admin login
- View all table reservations and takeaway orders
- Cancel customer reservations and orders
- Dashboard with analytics (e.g., bar charts of reservations)

---

## Tech Stack

- **Frontend:** React.js, Tailwind CSS, Vite
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Others:** Chart libraries for visualization, Form validation, Routing

---

## Folder Structure
AurumDining/
├── backend/                  # Node.js + Express server
│   └── server.js
├── restaurantfrontend/      # React frontend app
│   ├── src/
│   ├── public/
│   └── package.json
├── .gitignore
└── README.md