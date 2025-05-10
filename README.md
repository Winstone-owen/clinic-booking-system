# Clinic Booking System

## Description

This project implements a full-featured **Clinic Booking System** using MySQL. It enables management of patients, doctors, appointments, prescriptions, and medications. The database schema is fully normalized and follows best practices for relational database design, including primary keys, foreign keys, unique constraints, and proper relationship modeling (1-to-1, 1-to-many, and many-to-many).

## Features

* Manage patient and doctor profiles
* Schedule and manage appointments
* Link appointments to prescriptions
* Track prescribed medications per appointment
* Ensure no doctor is double-booked

## How to Run / Setup

1. **Install MySQL Server** if not already installed.
2. **Open a MySQL client** (e.g., MySQL Workbench, command-line).
3. **Run the SQL Script:**

   * Open and execute the `Clinic Booking System.sql` file.
   * This will:

     * Create the `ClinicBookingSystem` database.
     * Create all necessary tables with relationships and constraints.

```
mysql -u your_username -p < ClinicBookingSystem.sql
```



