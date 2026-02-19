# Fullstack Gym Management System

## Overview

This project is a full-stack gym management platform developed in an academic context as part of a Web and Mobile Development course.
The system was designed to support gym member management, access control, class scheduling and internal communication between administrators and users.

It includes both backend and frontend components, implementing authentication, role-based access control, QR code entry validation and real-time features such as notifications and access tracking.

The goal was to simulate a realistic software development process, from requirements definition to implementation and testing.

---

## Main Features

### User Roles

* **Normal User**

  * Access to gym equipment
  * Personal profile and QR code entry
  * View messages and class information

* **VIP User**

  * All normal features
  * Access to premium facilities (sauna, jacuzzi, etc.)
  * Ability to register for gym classes

* **Manager (Admin)**

  * User management
  * Class creation and editing
  * Access logs monitoring
  * Messaging system for members

---

## Key Functionalities

### Authentication & Access Control

* User registration with image upload
* Login with email/password or QR code
* Session management (expiration and logout)
* Role-based authorization

### Gym Access Management

* QR code entry system
* Access restrictions by user role
* Entry/exit tracking with timestamps
* Real-time gym occupancy counter

### Class Management

* Create, edit and delete classes
* Capacity control
* Class enrollment and cancellation
* Automatic notifications for new classes

### Communication System

* Manager-to-user messaging
* Notification feed
* Internal message inbox

### Additional Features

* Responsive web interface
* Search functionality across classes
* Image upload support
* Real-time updates using WebSockets

---

## Project Structure

```
Backend/   → API, authentication, business logic
Frontend/  → React web application
docs/      → Project documentation
```

---

## Technologies Used

### Backend

* Node.js
* Express.js
* MongoDB (data persistence)
* JWT authentication
* WebSockets

### Frontend

* React.js
* JavaScript (ES6)
* CSS
* REST API integration

### Other Tools

* QR code authentication
* Image upload middleware
* Testing with Jest
* Postman for API testing

---

## Documentation

Project documentation is available in the `docs/` directory, including:

* **Project specification document**
* **Academic project report**


These documents describe requirements, architecture, system features and development context.

---

## API Overview

Main API modules include:

### Users

* User registration and authentication
* Role management
* Profile access

### Classes

* Class scheduling
* Enrollment management
* Capacity control

### Gym Access

* QR-based entry validation
* Access logs
* Facility permissions

---

## How to Run

### Backend

```
cd Backend
npm install
npm start
```

### Frontend

```
cd Frontend
npm install
npm start
```

Ensure the backend server is running before starting the frontend.

---

## Learning Outcomes

This project demonstrates experience with:

* Full-stack development
* Authentication and authorization
* REST API design
* Real-time communication features
* Role-based system design
* Responsive frontend development
* Team-based academic software development

---

## Author Notes

This project was developed in a team academic environment.
My contribution focused mainly on development, integration and implementation of core system features.

---

## License

Academic project — for educational purposes.
