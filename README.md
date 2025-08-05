# SchoolDB - Simple SQL Project

## About

This is a basic school database project using *MySQL*. It includes three main tables:

- *Student*
- *Course*
- *Enrollment*

The project covers:
- Creating database and tables
- Using primary and foreign keys
- Inserting data (with default values and NULLs)
- Updating and deleting data
- Simple SQL queries and transaction

---

##  Tables

### Student
- student_id (Primary Key, Auto Increment)
- name
- age
- email
- grade (Default: 'NA')

### Course
- course_id (Primary Key)
- course_name
- credits (Default: 3)

### Enrollment
- enrollment_id (Primary Key)
- student_id (Foreign Key → Student)
- course_id (Foreign Key → Course)
- enrollment_date (Default: CURRENT_DATE)

---

## ▶ Features

- Insert students with partial data (NULLs/defaults)
- Add and manage course enrollments
- Use ON DELETE CASCADE to automatically delete enrollments if a student is deleted
- Update missing values (e.g., age)
- Delete records
- Use ROLLBACK with transactions
- Run simple queries (SELECT, INSERT, UPDATE, DELETE)

---


