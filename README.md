# MentalHealthApp Backend

This project provides the backend for the MentalHealthApp, an iOS application. The backend is built with Django and leverages Firebase Firestore for data storage and authentication. The application is deployed on AWS, providing a scalable and secure platform for hosting the application.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Architecture](#architecture)
4. [Setup and Deployment](#setup-and-deployment)
   - [Local Development](#local-development)
   - [AWS Deployment](#aws-deployment)
5. [Environment Variables](#environment-variables)
6. [License](#license)

## Project Overview

MentalHealthApp is an iOS application designed to support users' mental health by tracking their mood, activities, and providing helpful resources. This repository contains the backend code, which is responsible for handling API requests, storing user data, and authenticating users.

## Technologies Used

- **Django**: A high-level Python web framework used to build the backend.
- **Firebase Firestore**: A NoSQL document database for storing and syncing data in real-time.
- **Firebase Authentication**: Used for managing user authentication.
- **AWS Elastic Beanstalk**: A service for deploying and managing applications in the AWS Cloud.
- **Gunicorn**: A Python WSGI HTTP server for UNIX, used to serve the Django application.
- **Whitenoise**: Used to serve static files in a production environment.

## Architecture

The architecture of the MentalHealthApp backend integrates Firebase Firestore for data storage and authentication, with the application deployed on AWS for scalability and reliability.

User
|
v
HTTP Request
|
v
AWS (Django Application Server)
|
v
Firebase Firestore (Database)



- **Firebase Firestore**: Stores application data in a structured and scalable manner.
- **AWS**: Hosts the Django application, handling incoming HTTP requests and processing business logic.


