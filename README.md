# Student-login-portal

This project is a student registration and login system built with PHP, HTML, CSS, and PostgreSQL. It allows students to create an account, log in, and after loged-in students can edit specific details.

## Features
 Student Registration: Allows new users to create an account by providing necessary details such as name, email, password, etc.
 Login System: Authenticates registered students to allow access to the application.
 Password Encryption: Ensures that user passwords are stored securely in the database.
 Data Validation: Validates input data to prevent invalid or malicious entries.
 Error Handling: Provides error messages for failed login attempts, existing users, or incomplete registration.

## Installation

1. Clone the Repository:
   Clone the project from GitHub to your local machine.
   ```bash
   git clone https://github.com/Prem-Agravat/student-login-portal.git
   cd student-login-portal
   
2.Set up a Local Server:
   Run a local server such as XAMPP to support PHP applications. Ensure that Apache and PostgreSQL services are running in the XAMPP.

3.Configure Database Connection: 
   Open config.php in the project files and update it with your PostgreSQL credentials (database name, username, and password).

4.Database Setup:
  I created a database named ICT_Project. In this database, I added a table called user_info. The table includes attributes such as id (a unique identifier for each student), name (the student's full name), email (the student’s email address), password (encrypted password for secure login),image(the student's Profile image).
5.Run the Application: 
  Start your local server through XAMPP, then open a browser and go to
  http://localhost/register.php

## Usage
- Register as a new student.
- Log in with your student credentials.
