User System Database
Description

This project contains the database structure for a basic user management system.

The goal of the project is to practice database design and version control while building the foundation of a complete system.

Technologies

SQL

Microsoft SQL Server

Git

GitHub

Project Structure

database/

create_database.sql

create_tables.sql

insert_test_data.sql

Database Schema

The system currently includes a usuarios table with the following fields:

id (Primary Key, auto increment)

nombre

email (unique)

password

fecha_creacion

How to Run

Execute create_database.sql

Execute create_tables.sql

Execute insert_test_data.sql

These scripts will create the database and populate it with test data.

Future Improvements

Add authentication logic

Add roles and permissions

Connect database to backend API
