# HealthHub: Medical Clinic Database Management System

## Overview
HealthHub is a comprehensive relational database system designed to manage the operations of a medical clinic. This system is designed to improve efficiency and communication within a clinic by providing a centralized platform for handling information.

## Features
- Comprehensive Patient Records: Manage detailed information about patients, including personal details, medical history, and treatment records.
- Doctor Profiles and Scheduling: Maintain profiles for doctors, including their specialties, contact information, and availability for appointments.
- Appointment Scheduling: Efficiently schedule and manage patient appointments, including rescheduling and cancellations.
- Financial Management: Track and manage financial transactions, including billing, payments, and insurance claims.

## Entity-Relationship Diagram
The Entity-Relationship (ER) diagram provides a visual representation of the database schema, showcasing key entities, their attributes, and the relationships between them.

![image](https://github.com/user-attachments/assets/3ac80dcf-be64-47ae-91cb-5723a4cc538d)

## Normalization Process
To maintain data integrity and reduce redundancy, the database was normalized to Boyce-Codd Normal Form (BCNF). The normalization process included:

- 1NF: Ensured that all tables contain atomic values, with no repeating groups.
- 2NF: Eliminated partial dependencies, ensuring that all non-key attributes are fully dependent on the primary key.
- 3NF: Removed transitive dependencies so that non-key attributes depend only on the primary key.
- BCNF: Ensured that every functional dependency's determinant is a super key, achieving the highest normalization level to eliminate all redundancy.

## Unix Shell Menu Implementation
The system includes a Unix Shell menu implementation for command-line interactions, allowing users to drop, create, populate, and query tables efficiently.

## Oracle APEX Integration
HealthHub is integrated with Oracle APEX (Application Express) to provide a web-based interface for managing and interacting with the database.

![image](https://github.com/user-attachments/assets/6f70f3aa-4086-4970-a712-50a1a6d565d4)
