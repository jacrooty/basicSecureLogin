# Secure Authentication System
## Overview
This system provides a secure authentication solution using Flask and Vue.js. It allows users to register and log in securely.
### Features
* Secure registration and login functionality
* User data storage in a SQLite database
* Password hashing using bcrypt
* Secure session management using Flask-Session
* CSRF protection using Flask-WTF
## Getting Started
* Clone the repository: git clone https://github.com/your-username/secure-auth.git
* Install dependencies: pip install -r requirements.txt (Flask) and npm install (Vue.js)
* Set up your database: configure the SQLALCHEMY_DATABASE_URI variable in app.py
* Run the Flask server: flask run
* Run the Vue.js frontend: npm run serve
## Usage
* Users can register by providing an email and password.
* Users can log in by providing their email and password.
## Security Measures
* Input validation to prevent SQL injection and XSS attacks
* Secure password hashing using bcrypt
* Secure session management using Flask-Session
* CSRF protection using Flask-WTF
## Files
* app.py: Flask backend server
* Login.vue: Vue.js login component
* Register.vue: Vue.js registration component
* main.js: Vue.js main application file
### Contributing
Contributions are welcome! Please submit pull requests or open issues on GitHub.
### License
This project is licensed under the MIT License. See LICENSE for details.
