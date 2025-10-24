User Registration with Validation
Overview
This project implements user registration and login using Firebase Authentication along with comprehensive form validation on the frontend.

Features
Registration: Users can create an account with name, email, and password.
Validation: Registration and login forms validate input (email format, password strength, required fields).
Authentication: Uses Firebase Authentication (Email/Password).
Error Reporting: Users receive friendly error messages for invalid input or authentication errors.
Registration Process
User navigates to the registration page.
User enters:
Full Name (min 3 characters)
Email (must be valid)
Password (min 8 characters)
Confirm Password (must match)
Form validates all fields before submission.
If valid, registration uses Firebase Authentication to create the user.
On success, the user is redirected to the login page.
Login Process
User fills in email and password on the login page.
Form validation checks for:
Valid email format
Password length (min 6 characters)
Valid credentials are sent to Firebase Authentication for verification.
On success, user is redirected to the protected portfolio page.
Technologies Used
HTML/CSS for responsive and styled forms.
JavaScript for form validation and Firebase integration.
Firebase Authentication for storing user credentials securely.
File Structure
index.html - Login form and Firebase setup.
register.html - Registration form and Firebase setup.
assets/js/script.js - All frontend validation and authentication logic.
Prerequisites
Firebase project with Email/Password sign-in enabled.
Your Firebase config added in both index.html and register.html.
.
- Author: YOUR NAME or username

