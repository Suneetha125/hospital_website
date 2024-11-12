# Hospital Management System Project

This project aims to create a dynamic website for managing hospital operations. Below is the directory structure of the project:

```
hospital_management_final_project/
├── assets/
│   ├── css/                  # Stylesheets for the project
│   ├── js/                   # JavaScript files for client-side functionality
│   └── images/               # Images used in the website
├── config/
│   └── db.php                # Database connection configuration
├── public/
│   ├── index.php             # Homepage of the application
│   ├── register.php          # User registration page
│   ├── login.php             # User login page
│   ├── dashboard.php          # User dashboard after login
│   ├── book_appointment.php   # Page for booking appointments
│   ├── prescriptions.php      # Page for entering doctors' prescriptions
│   ├── cancel_appointment.php  # Page for canceling appointments
│   └── search_doctors.php     # Page for searching doctors by specialty
├── includes/
│   ├── header.php            # Header template for all pages
│   └── footer.php            # Footer template for all pages
├── controllers/
│   ├── register_user.php     # Handles user registration logic
│   ├── login_user.php        # Handles user login logic
│   ├── book_appointment.php   # Logic for booking appointments
│   ├── cancel_appointment.php  # Logic for canceling appointments
│   ├── enter_prescription.php  # Logic for entering prescriptions
│   └── search_doctors.php     # Logic for searching doctors
├── database/
│   └── init.sql              # SQL file for initializing the database
└── README.md                 # This documentation file
```

## Project Overview

### Features
1. User Registration
2. Appointment Booking
3. Entering Doctors' Prescriptions
4. Canceling Appointments
5. Searching for Doctors by Specialty

### Installation
1. Clone the repository or download the project files.
2. Set up a database and update the `config/db.php` file with your database credentials.
3. Run the local PHP server from the `public` directory:
   ```bash
   cd public
   php -S localhost:8000
   ```

4. Visit `http://localhost:8000` in your web browser to access the application.

### Contribution
Is this structure okay with everyone? Please provide any feedback or suggestions!
