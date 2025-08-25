# HOSPITAL-MANAGEMENT-SYSTEM-USING-DJANGO
The Hospital Management System developed using the Django framework is a comprehensive and efficient solution designed to streamline healthcare operations. The system prioritizes security and user authentication, ensuring that sensitive patient data is handled securely by different roles within the hospital staff. 

 Hospital Management System (Django)
 Overview

The Hospital Management System is a web-based application developed using the Django framework. It is designed to streamline hospital operations by providing secure, efficient, and user-friendly solutions for managing patients, doctors, staff, and appointments.

This project prioritizes security, scalability, and usability, ensuring that patient data is stored securely while allowing easy access to hospital staff based on their roles.

 Objectives

Maintain centralized patient records (personal details, history, treatment).

Provide online appointment scheduling with doctors.

Manage hospital staff roles & permissions.

Enable secure authentication & authorization for users.

Improve communication between patients and doctors.

📝 Features

**Patient Registration & Management
**Doctor Registration & Details Management
**Appointment Booking & Scheduling
**Role-based Authentication (Admin, Doctor, Patient)
**Django Admin Panel for Superusers
**Secure Login/Logout System
**Responsive UI (HTML, CSS, Bootstrap)
**Integration Ready (Payment Gateway, Labs, etc.)

  Tech Stack

Backend: Django (Python)
Database: SQLite / MySQL
Frontend: HTML, CSS, JavaScript, Bootstrap
Server: Django Development Server (or deploy on AWS/Heroku)

📂 Project Structure
hospital-management/
│-- hospital/               # Main project settings
│-- patients/               # Patient management app
│-- doctors/                # Doctor management app
│-- appointments/           # Appointment scheduling app
│-- templates/              # HTML templates
│-- static/                 # CSS, JS, images
│-- manage.py               # Django management script

 Installation & Setup

Clone Repository

git clone https://github.com/your-username/hospital-management.git
cd hospital-management


Create Virtual Environment & Activate

python -m venv venv
venv\Scripts\activate    # Windows
source venv/bin/activate # Mac/Linux


Install Dependencies

pip install -r requirements.txt


Run Migrations

python manage.py migrate


Create Superuser (Admin Panel Access)

python manage.py createsuperuser


Run Development Server

python manage.py runserver


👉 Open http://127.0.0.1:8000/
 in your browser.

 System Architecture

Django MVT (Model–View–Template) architecture.

Models define Patients, Doctors, Appointments.

Views handle business logic.

Templates render dynamic HTML pages.

Database stores patient & doctor records.

 Future Enhancements

 Online Payment Integration
 Prescription Upload & Download
 Automated Notifications (SMS/Email)
 Advanced Analytics Dashboard
 Multi-language Support

 Conclusion

This project demonstrates the implementation of a full-stack web application using Django for healthcare management. It improves efficiency in hospitals by reducing manual work and providing secure, accessible, and scalable digital solutions.

 Acknowledgments

Mentor: Mr. N. Junnu Babu (Asst. Professor, M.Tech, Ph.D.)
Organization: Slashmark IT – Internship Program
Internship Duration: May 31, 2024 – July 31, 2024

 Developed by D. Munibabu | B.Tech (CST)
