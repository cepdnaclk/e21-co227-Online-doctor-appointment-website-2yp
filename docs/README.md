---
layout: home
---

# Online Doctor Appointment Website (Group M)

This project is a web-based platform for scheduling and managing doctor appointments, developed as part of the CO227 - Software Systems course by Group M of the E21 batch.

## Project Overview

The Online Doctor Appointment system is designed to streamline the process of booking medical appointments. It provides a user-friendly interface for patients to find doctors, view their availability, and book appointments. It also offers separate dashboards for doctors and administrators to manage the system's operations.

### Key Features:
*   **Patient Portal**: Search for doctors by specialty, book appointments, view appointment history, and manage user profiles.
*   **Doctor Portal**: View and manage upcoming appointments, update profile information, and set availability.
*   **Admin Dashboard**: Oversee all platform activities, manage doctor and patient records, and view all appointments.
*   **Secure Authentication**: JWT-based authentication for secure access for all user roles (Patient, Doctor, Admin).
*   **Payment Integration**: Mock payment gateway for appointment booking fees.

## Our Team's Contribution

As Group M, our team was responsible for the end-to-end development of this full-stack application. Our specific contributions are broken down as follows:

### Frontend Development (Patient & Admin Portals)
*   **Technology**: React.js (Vite), Tailwind CSS.
*   **Description**: We designed and implemented the complete user interface for both the main patient-facing website and the administrative dashboard. This involved creating reusable components, managing application state, and ensuring a responsive design for various devices. We handled routing, API integration with the backend, and user authentication flows on the client side.

### Backend Development
*   **Technology**: Node.js, Express.js, MongoDB (with Mongoose).
*   **Description**: We built the entire RESTful API to support the application's functionalities. This included designing the database schema for users, doctors, and appointments. We implemented the business logic for user registration, login, appointment booking, and role-based access control using middleware. We also integrated with Cloudinary for image storage.

### System Architecture & Deployment
*   **Architecture**: We designed a clean, decoupled architecture with a separate frontend, backend, and admin panel, which communicate via REST APIs.
*   **Testing**: We performed comprehensive testing, including unit testing for individual components, integration testing to ensure seamless interaction between the frontend and backend, and performance testing with k6 to validate the system's stability under load.
*   **Deployment**: We prepared the application for deployment, including creating a comprehensive `README.md` with setup instructions for local development.

## Team Members

### Students
*   MADHUSHAN S.K.A.K. – E/21/245 (Team Leader)
*   DARSHANA K.M.S. – E/21/077
*   FONSEKA H.F.S.R. - E/21/140
*   ARNIKAN U. - E/21/036

### Coordinator
*   Ms. Yasodha Vimukthi 

## Technologies Used

*   **Frontend**: React, Vite, Tailwind CSS, Axios
*   **Backend**: Node.js, Express.js
*   **Database**: MongoDB (with Mongoose)
*   **Authentication**: JSON Web Tokens (JWT)
*   **Image Storage**: Cloudinary
*   **Testing**: Unit, Integration, and Performance (k6)

## Project Repository

The complete source code is available on GitHub:
[cepdnaclk/Online-doctor-appointment-website-2yp-e21](https://github.com/cepdnaclk/Online-doctor-appointment-website-2yp-e21)
