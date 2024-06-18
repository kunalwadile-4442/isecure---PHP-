## Project Description: Secure Login and Signup System

This project is a secure web application providing user authentication via login and signup services
. Users with an account can log in to access the home page, while new users can register. Passwords 
are securely stored using hashing algorithms to ensure protection. Built with PHP for backend processing 
and Bootstrap for frontend design, the system ensures that user data is secure and easily accessible.

### Features

1. **User Registration**: New users can sign up with a username, email, and password. Passwords are hashed using `password_hash()` before storage.
3. **User Login**: Registered users log in with their username and password, verified against the hashed passwords in the database using `password_verify()`.
4. **Home Page Access**: Successful login grants access to the home page, while unauthenticated users are redirected to the login page.
5. **Security**: Passwords are stored in hashed form, ensuring data security even if the database is compromised.

### Technologies

- **Backend**: PHP
- **Frontend**: Bootstrap, HTML.
