
# Teacher-Student Appointment Booking System

## Project Overview
The Teacher-Student Appointment Booking System is a web-based application designed to facilitate seamless scheduling of appointments between students and teachers. The system allows teachers to manage their availability, and students can view and book available slots. An admin panel is provided for managing users and appointments.

## Features
- User Authentication: Separate login for students and teachers.
- Appointment Booking: Students can view available slots and book appointments with teachers.
- Admin Panel: Admins can manage users, view appointments, and monitor the system.

## Tech Stack
- Backend: Python, Django
- Database: MySQL
- Frontend: HTML, CSS, JavaScript
- Tools : Django Admin, MySQL Workbench

## System Workflow
1. User Registration : Students and teachers register and log in.
2. Teacher Availability : Teachers view approved appointments 
3. Booking : Students view appointments and book slots.
5. Admin Management : Admin manages users and appointments through a dedicated panel.

## Database Design
The system uses three primary tables:
1. Users Table : Stores user information (students and teachers).
2. Appointments Table : Records appointment details, including student, teacher, date, and time.


### Prerequisites
- Python (>= 3.8)
- Django (>= 4.x)
- MySQL Server
- MySQL Client for Python (`mysqlclient`)

