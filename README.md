# Kutumb 

**Kutumb** is a society management web application designed to digitize and simplify day-to-day residential society operations.

I built Kutumb after seeing how my father, as a society president, managed society activities through **WhatsApp groups, paper records, and manual communication**. The goal was to bring these tasks into one organized platform.

##  Features

*  Role-based authentication for **Admin, Resident, Staff, and Security**
*  Complaint registration and staff assignment
*  Society billing and late-fee management
*  Facility booking with clash detection
*  Visitor management with QR-based visitor passes
*  Society notices and announcements
*  Emergency/SOS functionality
*  Dashboard with society-related insights

## 🛠️ Tech Stack

**Frontend:** React.js, Vite
**Backend:** Node.js, Express.js
**Database:** MongoDB, Mongoose
**Authentication:** JWT, bcrypt
**Deployment:** Vercel, Render, MongoDB Atlas

##  Architecture

```text
React Frontend
      ↓
REST APIs
      ↓
Express.js Backend
      ↓
Authentication & Business Logic
      ↓
MongoDB
```

The application follows a **client-server architecture**, with the React frontend communicating with the Express backend through REST APIs.

##  Key Highlights

* 4 different user roles
* 30+ REST API endpoints
* 8 MongoDB collections
* Role-based authorization
* Facility booking conflict detection
* Visitor and complaint management

##  Goal

Kutumb aims to replace scattered **WhatsApp messages and paper-based processes** with a centralized and structured society management system.
