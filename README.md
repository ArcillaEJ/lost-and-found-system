# FINDIT - Lost and Found Management System

## Project Overview

FINDIT is a web-based Lost and Found Management System developed using CodeIgniter 4. The system provides a centralized platform where users can report lost or found items, browse available reports, submit claims, and provide item update reports. Administrators can manage reported items, review user submissions, and monitor recovery activities through an administrative dashboard.

The objective of the system is to improve the efficiency of item recovery by replacing manual lost-and-found processes with a secure and organized digital solution.

---

## Live Deployment

### Live URL

https://finditlostandfound.infinityfreeapp.com

### Hosting Provider

InfinityFree Hosting

---

## Features

### User Module

* User Registration
* User Login and Logout
* Report Lost Items
* Report Found Items
* Upload Item Images
* Browse Reported Items
* Search and Filter Items
* View Item Details
* Submit Claim Requests
* Submit Item Update Reports

### Admin Module

* Dashboard Monitoring
* View Reported Items
* Manage Item Status
* Mark Items as Found
* Mark Items as Recovered
* Review Claim Requests
* Approve or Reject Claims
* Review Item Update Reports

---

## Technologies Used

### Backend

* PHP
* CodeIgniter 4

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

### Database

* MySQL

### Development Tools

* XAMPP
* Visual Studio Code
* Git
* GitHub

### Deployment

* InfinityFree Hosting

---

## Security Features

The system implements several security mechanisms to protect user information and application functionality.

### Authentication and Authorization

* Session-based authentication
* Role-based access control
* Admin route protection

### Cross-Site Request Forgery (CSRF)

* CodeIgniter CSRF protection enabled
* CSRF tokens included in form submissions

### Cross-Site Scripting (XSS) Prevention

* Escaped output using CodeIgniter helper functions
* Sanitized user-generated content

### Input Validation

* Required field validation
* Image upload validation
* Server-side validation rules

### Database Security

* CodeIgniter Query Builder
* Protection against SQL Injection attacks

---

## Testing and Debugging

### PHPUnit Testing

The system was tested using PHPUnit.

Results:

* 3 Test Cases Executed
* 5 Assertions Passed
* No Failed Tests

### Debugging

CodeIgniter's `dd()` function was used during development to inspect request data and validate application behavior.

---

## Deployment Process

1. Created InfinityFree hosting account.
2. Created production MySQL database.
3. Exported local database using phpMyAdmin.
4. Imported database into production server.
5. Uploaded CodeIgniter project files.
6. Updated application configuration.
7. Configured production database credentials.
8. Verified routing and authentication.
9. Tested all major system functions.
10. Published the application through the live URL.

---

## Documentation

The following documentation is included inside the repository.

### docs/

* Security_Report.pdf
* Deployment_Log.pdf
* PHPUnit_Result.png
* DD_Debugging.png
* Live_URL_Screenshot.png

### screenshots/

* Login Page
* User Dashboard
* Browse Items
* Item Details
* Claim Request
* Admin Dashboard
* Admin Items Management

---

## System Architecture

The system follows the Model-View-Controller (MVC) architecture provided by CodeIgniter 4.

### Models

* UserModel
* ItemModel
* ClaimModel
* ItemUpdateModel

### Controllers

* Auth Controller
* Item Controller
* Admin Controller

### Views

* Authentication Pages
* User Dashboard
* Item Management Pages
* Admin Dashboard

---

## Repository Structure

```text
app/
public/
tests/
writable/
docs/
screenshots/
README.md
composer.json
```

## Developers

Bachelor of Science in Information Technology

National Teachers College

Academic Year 2025–2026

---

## Conclusion

FINDIT provides a secure, organized, and accessible platform for managing lost-and-found activities. Through user reporting, claim management, administrative monitoring, and online deployment, the system improves the efficiency of recovering lost items while maintaining security and usability.
