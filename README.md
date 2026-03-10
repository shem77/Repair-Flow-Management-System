# Repair-Flow: Technical Service Management System

## Overview
Repair-Flow is a Java-based backend solution designed to manage the lifecycle of an electronics repair business. This system bridges the gap between hardware technical services and digital record-keeping, allowing for efficient tracking of customer devices, repair statuses, and financial balances.

## Key Features
* **Secure CRUD Operations:** Full implementation of Create, Read, Update, and Delete functions for repair records.
* **Database Persistence:** Integration with MySQL using JDBC for reliable data storage.
* **Financial Tracking:** Automated calculation of balance due based on 70% deposit requirements.
* **Data Security:** Implementation of Parameterized Queries to prevent SQL Injection attacks.
* **Search Engine:** Fast retrieval of customer records using phone number indexing.

## Tech Stack
* **Language:** Java 17+
* **Database:** MySQL 8.0
* **API:** JDBC (Java Database Connectivity)
* **Tools:** VS Code / IntelliJ IDEA

## Business Logic
The system enforces a 70% deposit rule for all repair intakes to ensure hardware procurement costs are covered, minimizing financial risk for the service provider.

## How to Run
1. Clone the repository.
2. Import the `RepairShopDB.sql` schema into your MySQL server.
3. Update `DatabaseConnection.java` with your local credentials.
4. Compile and run `Main.java`.
