# Project Management System

This project is a web application designed for managing projects and skills. It includes features for adding and deleting projects, as well as managing skills. The admin panel provides login and registration functionality to control access.

## Features

- **Project Management:**
  - Add new projects with details like name, description, and technology stack.
  - Delete existing projects from the database.
  
- **Skill Management:**
  - Add skills to the platform.
  - Delete skills from the platform.

- **Admin Panel:**
  - Admins can register and login to manage projects and skills.

## Technologies Used

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB (with Mongoose)
  
- **Frontend:**
  - HTML
  - CSS
  - JavaScript

## Installation

### Prerequisites

- Node.js (version 14 or later)
- MongoDB (or MongoDB Atlas)

### Steps to Run Locally

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
2. Navigate to the project directory:

    ```bash
    cd your-repository-name
3. Install the dependencies:

    ```bash
    npm install
4. Create a .env file in the root directory and add your MongoDB credentials:

   ```bash
   DBUSER=your-mongo-db-username
   DBPWD=your-mongo-db-password
   DBHOST=your-mongo-db-host
   DBNAME=your-database-name
   SESSIONSECRET=your-session-secret
5. Start the application:

    ```bash
    npm start
6. The application will be available at http://localhost:8000. 
