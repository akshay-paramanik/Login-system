# Login-system
This project is a proper login system built using the Laravel Framework, featuring robust session management for secure user authentication.


**#Overview**
The Laravel Login System provides a secure and efficient way to authenticate users, featuring proper session handling. This project can be easily integrated into any Laravel-based application.


**#Features**
User Registration,
Secure Login with session-based authentication,
Logout functionality to clear sessions,
Middleware for route protection based on authentication status,


**#Technologies Used**
Framework: Laravel,
Frontend: Blade templates, HTML, CSS,
Backend: Laravel (PHP),
Database: MySQL.



**#Setup and Installation**
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/laravel-login-system.git
Navigate to the project directory:

bash
Copy code
cd laravel-login-system
Install dependencies:

bash
Copy code
composer install
Configure the .env file:

env
Copy code
APP_NAME="Laravel Login System"
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
Run migrations to set up the database:

bash
Copy code
php artisan migrate
Start the Laravel development server:

bash
Copy code
php artisan serve
Access the application:

http://localhost:8000
Usage
Navigate to the Register page to create a new account.
Log in with your credentials to access protected routes.
Use the Logout button to end the session securely.
Screenshots
Login Page

Registration Page
