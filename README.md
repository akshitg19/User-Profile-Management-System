# User Profile Management System

This project is a full-stack web application that allows users to upload and manage their profile pictures. It uses **Spring Boot** for the backend, **React.js** for the frontend, and **AWS S3** for file storage.

## Features
- User authentication and profile management
- Profile picture upload with AWS S3
- REST API for user operations
- Responsive UI using React

## Technologies Used
- **Frontend**: React.js, HTML, CSS
- **Backend**: Spring Boot, Java
- **Database**: PostgreSQL
- **Storage**: AWS S3
- **Build Tools**: Maven, Docker

## Setup Instructions

### Prerequisites
- Java 11+
- Node.js
- Maven
- AWS Account

### Backend (Spring Boot)

1. Clone the repository:
   ```bash
   git clone https://github.com/akshitg19/User-Profile-Management-System.git
   cd User-Profile-Management-System
   ```

2. Configure your AWS credentials in `application.yml`.

3. Build and run the backend:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend (React)

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies and run the app:
   ```bash
   npm install
   npm start
   ```

## Credits
This project is based on the tutorial by [Amigoscode](https://www.youtube.com/c/Amigoscode). 

