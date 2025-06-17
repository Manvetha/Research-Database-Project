![image](https://github.com/user-attachments/assets/dbed0bf2-7ea8-4fa3-801a-9128b8dd8664)


Project Title: Research Projects Database Management System

Description:

In this project, I designed and implemented a relational database system to manage information related to research projects, their funding agencies, and employees involved. The goal was to create a structured database that can efficiently store and retrieve information about multiple research projects, their assigned employees, and associated funding details.

Key Components:

Entity-Relationship Design:

Modeled entities such as Project, Employee, and FundingAgency.

Designed relationships to represent which employees are assigned to which projects, who manages each project, and which agency funds which project.

Database Tables and Structure:

project: Stores project details like Project_ID, Name, Duration, and Budget.

fundingagency: Contains funding agency information including Agency_ID, Name, and Address.

employee: Holds employee data such as SSN, Emp_Name, and Salary.

employee_project: A junction table mapping employees to the projects they work on, including the Manager_SSN.

project_manager: Defines the manager of each project separately for clarity and referential integrity.

Constraints & Keys:

Applied primary and foreign key constraints to ensure data integrity.

Implemented composite primary keys where necessary (e.g., in employee_project and project_manager).

Data Insertion:

Populated each table with sample data to demonstrate the database functionality.

Example projects include "AI Research", "Robotics Development", and "Cybersecurity Audit".

This project simulates a real-world scenario of managing research activities, employees, and funding sources in an academic or corporate environment using SQL.

![image](https://github.com/user-attachments/assets/1ffe52bb-152a-4e0e-96b1-453040c5c84e)
