🩸 Blood Donation Management System

A web-based Blood Donation Management System developed using PHP & MySQL.
This system helps manage donors, recipients, blood stock, donation requests, and notifications efficiently.

📌 Features

User authentication (Register, Login, Logout)

Donor, Recipient, and Admin dashboards

Blood stock management

Blood donation requests & request status tracking

Donor eligibility check & donation history

Reports and statistics

Email notifications (PHPMailer)

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Mailer: PHPMailer

📂 Project Structure
blood-donation/
│── index.php               # Homepage
│── login.php               # User login
│── register.php            # User registration
│── logout.php              # Logout
│── contact.php             # Contact page
│
├── assets/css/style.css    # Stylesheet
│
├── includes/               # Common includes
│   ├── db.php              # Database connection
│   ├── functions.php       # Helper functions
│   ├── header.php          # Header template
│   └── footer.php          # Footer template
│
├── dashboard/              # User dashboards
│   ├── admin/              # Admin features
│   ├── donor/              # Donor features
│   └── recipient/          # Recipient features
│
├── requests/               # Blood requests
├── reports/                # Reports module
├── notifications/          # Notifications
├── search/                 # Donor & request search
└── vendor/phpmailer/       # Email notifications

🚀 Installation

Clone this repository:

git clone https://github.com/your-username/blood-donation.git


Move the project to your XAMPP/htdocs folder.

Import the MySQL database (blood_donation.sql) into phpMyAdmin.

Update includes/db.php with your database credentials.

Start Apache & MySQL in XAMPP.

Open the project in browser:

http://localhost/blood-donation/

🔑 Default Login Credentials

(Admin / Donor / Recipient credentials can be added after database import.)

Admin:    admin@example.com | password
Donor:    donor@example.com | password
Recipient: recipient@example.com | password

📧 Email Notifications

Configured using PHPMailer.

Update SMTP details in vendor/phpmailer/ or configuration file.

📸 Screenshots

(Add screenshots of dashboards here once hosted.)

🤝 Contribution

Contributions are welcome! Fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License.
