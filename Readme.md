# Employee Management System

## Overview
The **Employee Management System** is a web-based application designed to facilitate employee and customer management. The system allows employees to log in, manage customers, process transactions, and handle loan management tasks efficiently.

## Features

### 1. Employee Registration (US001)
- Employees can register by providing their details.
- A unique **7-digit Employee ID** is auto-generated upon registration.
- Required fields:
  - First Name (Max 50 characters)
  - Last Name (Max 50 characters)
  - Email
  - Password (Max 30 characters)
  - Confirm Password (Must match Password)
  - Address (Max 100 characters)
  - Contact Number (Max 10 characters)
- Success message displayed: **"Employee Registration Successful"**
- Registration is static and does not require database integration.

### 2. Employee Login (US002)
- Employees log in using:
  - **Employee ID** (Auto-populated 7-digit number)
  - **Password** (Provided during registration)
- Clicking the 'Login' button:
  - Displays a success popup **"Employee Registration Successful"**
  - Redirects the employee to the Home Page.

### 3. Customer Management (US003, US004, US005)
#### a. Customer Registration (US003)
- Employees can capture new customer information by entering:
  - Customer SSN ID
  - Customer Name
  - Account Number
  - IFSC Code
  - Account Balance
  - Aadhaar Card No.
  - PAN Card No.
  - Date of Birth
- Displays **"Customer Registration Successful"** popup upon success.

#### b. Edit Customer Information (US004)
- Employees can **view and update** customer details.
- **SSN updates are not permitted**.
- Displays **success/error response** messages.

#### c. Delete Customer (US005)
- Employees can **view details before deleting**.
- Displays **success/error response** messages.

### 4. Transaction Processing (US006)
- Employees can capture transaction details by entering:
  - Transaction ID
  - Customer SSN ID
  - Customer Name
  - Account ID
  - Aadhaar Card No.
  - PAN Card No.
  - Address
  - Date
  - Contact Number

### 5. Loan Management (US007)
- Employees can **update or cancel** a loan request.
- Employees **can view details before updating or deleting**.
- **SSN updates are not permitted**.
- Displays **success/error response** messages.

## Acknowledgment Messages
- Employee Registration: **"Employee Registration Successful"** (Green color)
- Customer Registration: **"Customer Registration Successful"**
- Success/Error responses displayed where applicable.

## Notes
- The system does **not require database integration** at this stage.
- The Employee ID is **auto-generated and non-editable**.
- All forms follow UI best practices with **user-friendly messages** and **input validation**.

---

This document provides an overview of the system's features and functionality. Let me know if any modifications are required! 🚀