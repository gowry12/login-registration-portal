# login-registration-portal
This project is a secure and user-friendly login and registration portal built using Flask. It allows users to register with their email and password, verify their email using a code sent to their inbox, and securely log in to access the portal. The portal ensures email verification before granting access to user-specific content.

##Technologies Used
Backend: Flask (Python), Flask-Login, Flask-Mail, SQLAlchemy
Database: SQLite
Frontend: HTML, CSS
Security: Password hashing with Werkzeug

##Features
User registration with email and password
Email verification with a 6-digit code
Secure login and logout functionality
User session management

##Installation and Usage Instructions
Prerequisites
Python installed on your system (version 3.7 or higher).
A Gmail account to configure email sending.

##installation
Configure email settings in app.py:
Replace your_secret_key with a secure secret key.
Replace MAIL_USERNAME and MAIL_PASSWORD with your email and app password.

##Initialize the database:
python app.py
The database users.db will be created automatically.

##Running the Application
Start the Flask development server:
python app.py
Open your web browser and navigate to:
http://127.0.0.1:5000

##Usage
Register: Provide your email and password to create an account. You will receive an email with a verification code.
Verify Email: Enter the code to verify your email address.
Login: Use your verified email and password to log in.
Logout: Click the "Logout" button to end your session.

##Screenshots
Welcome Page
Registration Page
Login Page
Email Verification
Home Page

