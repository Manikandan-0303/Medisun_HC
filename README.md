# Medisun Healthcare Cloud Deployment Project

![Medisun Healthcare](https://via.placeholder.com/1200x400?text=Medisun+Healthcare)

Medisun Healthcare is a cloud-based healthcare management system designed to facilitate disease prediction (diabetes, heart disease, breast cancer), patient registration, doctor scheduling, and appointment management. This project is built using Django as a web framework and is deployed on AWS and PythonAnywhere platforms. It allows users to access the system from anywhere across the world using smart devices such as smartphones or computers.

## Features

### Disease Prediction
- Predicts three different diseases:
  - Diabetes
  - Heart Disease
  - Breast Cancer

### User Registration
- Patients and doctors can register accounts.

### Doctor Features
- Creation of schedules.
- Viewing scheduled appointments.

### Patient Features
- Selection of doctors from different specialties.
- Appointment scheduling with chosen doctors.

## Technologies Used
- **Django** (Web Framework)
- **SQLite3** (Database)
- **AWS** (Cloud Platform)

## Deployment

The project is deployed on cloud platforms:
- **AWS:** The primary deployment platform for Medisun Healthcare.

## Accessing the Application

Users can access the deployed website using any modern web browser on their smart devices (smartphones, tablets, computers). They can navigate to the website URL to access the features of Medisun Healthcare.

## Setting Up Development Environment

1. Clone the repository from GitHub.
2. Install Python and Django on your development machine.
3. Set up MySQL database and configure database settings in the Django project.
4. Run migrations to create necessary database tables.
5. Start the Django development server to test the application locally.

## File Structure

├── manage.py # Django management script
├── medihealth/ # Django project directory
│ ├── settings.py # Django settings file
│ ├── urls.py # URL configuration file
│ ├── views.py # Views for handling web requests
│ ├── models.py # Database models
├── templates/ # HTML templates
├── static/ # Static files (CSS, JavaScript, images)
├── apps/ # Django apps directory (e.g., user authentication, appointment scheduling)
├── migrations/ # Database migration files
└── README.md # Readme file for the project
