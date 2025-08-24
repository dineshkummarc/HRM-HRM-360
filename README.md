# HRM 360

HRM 360 is an integrated Human Resource Management System designed to streamline and optimize HR processes within an organization. Built on the latest version of the CodeIgniter framework, HRM 360 offers a comprehensive suite of features to manage recruitment, promotions, performance management, training, payroll, and employee services, enhancing operational efficiency and employee engagement.

## Features

- 360-Degree Feedback: Collect feedback from superiors, peers, and coworkers to foster a culture of accountability and continuous improvement.
- Recruitment and Promotion: Manage job postings, applications, and promotion processes seamlessly.
- Performance Management: Track and evaluate employee performance with detailed reports and analytics.
- Training and Development: Organize training sessions and track employee progress.
- Payroll Management: Handle payroll, bonuses, loan deductions, provident funds, and more.
- Attendance and Leave Management: Simplify attendance tracking and leave requests with comprehensive reporting.
- Employee Management: Centralized management of employee data, roles, departments, and designations.
- Financial Management: Manage estimates, invoices, and billing efficiently.
- User-Friendly Interface: Intuitive and responsive design for easy navigation and use.
## Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Composer
- Node.js and npm
## Installation

Clone the repository:

```bash
  git clone https://github.com/Jeethanxx01/HRM.git
  cd hrm360
```
Install dependencies:

```bash
  composer install
  npm install
```
Configure the environment:

Copy the .env.example file to .env and update the necessary configurations.

```bash
  cp .env.example .env
```
Set up the database:

Create a database and update the database configuration in the .env file. Then run the migrations:
```bash
  php artisan migrate --seed
```
Run the application:

```bash
php artisan serve
```
Your application should now be running at http://localhost:8000.
    
## Login Credentials

Admin Login
- Email: jhondoe@hrm360.ac.in
- Password: admin123456

Employee Login
- Email: janedoe@hrm360.ac.in
- Password: ep123456
## Screenshots

Dashboard Overview
![App Screenshot](https://github.com/Jeethanxx01/HRM/blob/main/images/Dashboard.png)

Employee Management
![App Screenshot](https://github.com/Jeethanxx01/HRM/blob/main/images/employee%20management.png)

Project Management
![App Screenshot](https://github.com/Jeethanxx01/HRM/blob/main/images/project%20management.png)

Payroll Management
![App Screenshot](https://github.com/Jeethanxx01/HRM/blob/main/images/payroll%20management.png)

Attendance and Leave Management
![App Screenshot](https://github.com/Jeethanxx01/HRM/blob/main/images/attendance%20management.png)
## License

This project is licensed under the MIT License - see the LICENSE file for details.
[MIT](https://github.com/Jeethanxx01/HRM/blob/main/LICENSE)
