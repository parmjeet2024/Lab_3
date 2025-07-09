HR Management System - Parmjeet
Project Overview
This JavaFX application is a simple HR Management System built for Lab 3. It provides a login page, a dashboard, an admin page, and an employee page. Users can log in with their email and password, manage employee records, and navigate between pages.

Features
Login Page

Email and password fields

Validates login using in-memory sample data

Dashboard

Shows a welcome message

Buttons for navigating to Admin, Employee, Logout, and Exit

Admin Page

View, create, update, and delete employee records

Manage roles and salaries

Back to Dashboard and Logout options

Employee Page

Similar features as Admin Page but focused on employee records only

Sample Data

Uses EmployeeData with sample employees

Supports login with preset credentials

How to Run
Requirements

Java 11 or higher

JavaFX SDK installed

IDE such as VS Code or IntelliJ IDEA

Setup

Clone this repository or download the source code.

Make sure JavaFX SDK is configured properly in your IDE.

Make sure all .java files are inside the src folder.

Run

Run Main.java to start the application.

Use the following sample login credentials:

makefile
Copy
Edit
Email: harman@company.com
Password: admin123
Project Structure
css
Copy
Edit
src/
 ├── Main.java
 ├── LoginPage.java
 ├── DashboardPage.java
 ├── AdminPage.java
 ├── EmployeePage.java
 ├── LoginDAO.java
 ├── EmployeeData.java
 ├── Employee.java
Sample Employee Credentials
Name	Email	Password	Role	Salary
Harman Admin	harman@company.com	admin123	Admin	80000
Navdeep Singh	navdeep@company.com	nav123	Employee	55000
Harjot	harjot@company.com	harjot123	Employee	60000
Chamkila	chmkila@company.com	chamkila123	Employee	52000

Notes
This project uses only in-memory data for demonstration.

No actual database connection is used.

The UI is built using JavaFX layout managers (VBox, HBox, GridPane).

TableViews display employee data with support for Create, Update, Delete, and View All.

Author
Parmjeet Singh
Lab 3 - HR Management System
