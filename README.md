# Smart Medical Appointment Booking System

A full-stack medical appointment booking platform that enables patients to book appointments with doctors online, while providing dedicated Admin and Doctor management panels for efficient healthcare operations.

## Live Demo

### Patient Portal

https://appointment-frontend-943b.onrender.com

### Admin Panel

https://appoinment-admin.onrender.com

## Features

### Patient Features

* User registration and authentication
* Browse available doctors
* View doctor profiles and specialties
* Book appointments online
* Manage personal profile
* View appointment history
* Cancel appointments

### Admin Features

* Secure admin authentication
* Add and manage doctors
* View all appointments
* Monitor platform statistics
* Manage healthcare operations through a dedicated dashboard

### Doctor Features

* Doctor profile management
* Appointment management
* Availability tracking
* Patient appointment overview

## Tech Stack

### Frontend

* React.js
* Vite
* React Router DOM
* Axios
* React Toastify

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Multer
* Cloudinary

### Deployment

* Render
* MongoDB Atlas

## Project Structure

```text
Smart-Medical-Appoinment-Booking-System/
├── backend/
├── frontend/
└── admin/
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Smart-Medical-Appoinment-Booking-System.git
cd Smart-Medical-Appoinment-Booking-System
```

### Backend Setup

```bash
cd backend
npm install
npm run server
```

Create a `.env` file inside the backend directory:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=your_admin_password

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Create a `.env` file inside the frontend directory:

```env
VITE_BACKEND_URL=http://localhost:4000
```

### Admin Setup

```bash
cd admin
npm install
npm run dev
```

Create a `.env` file inside the admin directory:

```env
VITE_BACKEND_URL=http://localhost:4000
```

## API Overview

### User APIs

* User Registration
* User Login
* Profile Management
* Appointment Booking
* Appointment Cancellation

### Admin APIs

* Admin Login
* Add Doctor
* Manage Doctors
* View Appointments
* Dashboard Analytics

### Doctor APIs

* Doctor Login
* Doctor Profile Management
* Appointment Management

## Security Features

* JWT-based Authentication
* Password Hashing using Bcrypt
* Protected Routes
* Role-based Access Control
* Secure Environment Variables

## Future Enhancements

* Online Payments
* Email Notifications
* Video Consultations
* Prescription Management
* Medical Records Storage
* Appointment Reminders

## Author

**Mohd Gilman Khan**

## License

This project is licensed under the MIT License.
