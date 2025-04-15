# Fleet Management System

A comprehensive fleet management solution built with:

- Frontend: HTML, Tailwind CSS, JavaScript
- Backend: PHP
- Database: MySQL (phpMyAdmin)

link:  https://fleet-pro.infinityfreeapp.com/

## Features

- User authentication (login/register)
- Vehicle management (CRUD operations)
- Driver management (CRUD operations)
- Dashboard with fleet statistics
- Responsive design for all devices
- Real-time updates
- Secure authentication

## Installation

1. Import the database schema from `sql/setup.sql` to your MySQL database
2. Configure database connection in `includes/config.php`:
change these to this if you want to run locally
   ```php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'your_username');
   define('DB_PASS', 'your_password');
   define('DB_NAME', 'fleet_management');
   ```
3. Deploy files to your web server
4. Access the application through your browser

## Default Credentials

- Email: admin@fleetpro.com
- Password: password

## File Structure

```
fleet-management/
├── assets/            # Static assets
├── includes/          # PHP includes
│   ├── auth.php       # Authentication functions
│   ├── config.php     # Database configuration
│   └── db.php         # Database operations
├── sql/               # Database schema
│   └── setup.sql      # Database setup script
├── about.php          # About page
├── dashboard.php      # Dashboard
├── drivers.php        # Driver management
├── index.php          # Landing page
├── login.php          # Login page
├── logout.php         # Logout handler
├── register.php       # Registration page
└── vehicles.php       # Vehicle management
```

## Technical Requirements

- PHP 7.4+
- MySQL 5.7+
- Web server (Apache)
