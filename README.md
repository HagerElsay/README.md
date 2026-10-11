# Hospital Database Management System

A beginner healthcare database project built with Python and SQLite to organize hospital patient records, doctors, departments, and appointments.

## Features

- Patient record management
- Doctor and department management
- Appointment scheduling and tracking
- SQL relationships using foreign keys
- Data validation and basic duplicate prevention
- Hospital analytics and summary reports
- SQL queries using SELECT, WHERE, JOIN, COUNT, and GROUP BY
- Database integrity testing

## Database Tables

1. "patients" — Patient information and diagnoses
2. "doctors" — Doctor information and specialties
3. "departments" — Hospital departments and locations
4. "doctor_departments" — Relationships between doctors and departments
5. "appointments" — Patient appointments, doctors, dates, and statuses
6. "validated_patients" — Demonstration table for database constraints

## Technologies

- Python
- SQLite
- SQL
- Pydroid 3 (Android development environment)

## Testing Results

- 6 database tables verified
- 4 patient records in the main patients table
- 3 doctors
- 4 departments
- 3 appointments with valid patient and doctor relationships
- Foreign key integrity check passed
- Data validation constraints tested

## Project Purpose

This project demonstrates foundational database skills relevant to healthcare data management and healthcare technology infrastructure.

## Future Improvements

- Connect the database to a healthcare REST API
- Improve patient identity matching
- Strengthen validation and duplicate detection
- Add authentication, authorization, and audit logging
- Implement secure handling of sensitive health information

## Disclaimer

This is an educational prototype using fictional patient records. It is not intended for real hospital use or the storage of actual patient data.
