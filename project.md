![image](https://github.com/user-attachments/assets/e6441e53-fc51-4d84-9cba-2fa18667a7ed)


Project Title: University Exam Management System

Description:

This project involves the design and implementation of a relational database system to manage the examination process in a university environment. The system captures and organizes information about students, faculty members, departments, courses, and exams. It ensures seamless data handling for academic and administrative purposes.

Key Features of the Project:

Entities and Relationships:

Departments: Each department has a unique ID, name, and is managed by a faculty member (Head of Department).

Faculty: Includes faculty ID, name, and designation. A faculty member can teach and coordinate multiple courses, and also head a department.

Courses: Every course has a unique code and is linked to a specific department. Courses are taught and coordinated by faculty.

Students: Each student has a roll number and belongs to a department. Students can enroll in multiple courses.

Exams: Created and conducted by faculty, each exam is associated with a course. Exams have attributes like title, type (internal/external), duration, and date.

Database Tables:

Department: Stores department ID, name, and head of department.

Faculty: Contains details of faculty members.

Course: Maps courses to departments.

Student: Holds student details and their respective departments.

Exam: Contains data about exams conducted, including type and scheduling.

Data Relationships:

Foreign key constraints are used to establish relationships between tables, such as:

head_id in Department referencing Faculty

dept_id in Course and Student referencing Department

faculty_id and course_code in Exam referencing Faculty and Course respectively

Sample Data:

Faculty members like Dr. A. Sharma and Prof. B. Kumar

Departments such as Computer Science and Mechanical Engineering

Courses like Data Structures and Thermodynamics

Students including Alice Thomas and Rahul Verma

Exams such as Midterm DS and Endterm TD

Conclusion:

This SQL project provides a robust and normalized schema for a university examination system. It accurately models real-world academic scenarios and ensures efficient data storage and retrieval using relational database principles.

![image](https://github.com/user-attachments/assets/6b80cbd2-6ae8-4a40-89ed-56e9fba267ce)
