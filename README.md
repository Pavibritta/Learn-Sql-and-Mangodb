# Learn-Sql-and-Mangodb
During my internship i am learn database.
# Database Learning Practice

This repository shows my practice and learning in **MongoDB** and **SQL** databases.

## MongoDB Practice

Technologies used:

* MongoDB


### Created databases

* library
* office
* shop
  
## Learnings
* How to Create DB
* and Insert collections
* How to find and read
* how to update
* how to delete
* and i use Mongodb Compass method and Practice in powerShell also
### MongoDB Screenshots

https://github.com/Pavibritta/Learn-Sql-and-Mangodb/issues/2

---
## Connect with node.js

https://github.com/Pavibritta/Learn-Sql-and-Mangodb/issues/3

## SQL Practice

Database used: MySQL

### Topics Learned

* Creating tables
* Insert queries
* Select queries
* Filtering data with WHERE clause
## Basic queries

1. Create Database
CREATE DATABASE Amazon_crud;
2. Use Database
USE Amazon_crud;
3. CREATE TABLE `categories` (
  `category_id` int(11) NOT NULL,
  `category_name` varchar(100) NOT NULL,
  `description` text DEFAULT NULL,
  `created_at` timestamp NOT NULL DEFAULT current_timestamp()
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

4.Insert Data
INSERT INTO employees (name, age, department)
VALUES 
('Ravi', 30, 'IT'),
('Meena', 28, 'Finance');

5.Read Data

SELECT * FROM employees;
6.Update Data

UPDATE employees
SET age = 26
WHERE name = 'Pavithra';

7.Delete Data
DELETE FROM employees
WHERE id = 2;
## screenShorts

https://github.com/Pavibritta/Learn-Sql-and-Mangodb/issues/4


