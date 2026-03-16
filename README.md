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

4.CREATE TABLE `products` (
  `product_id` int(11) NOT NULL,
  `category_id` int(11) DEFAULT NULL,
  `product_name` varchar(150) NOT NULL,
  `price` decimal(10,2) NOT NULL,
  `stock` int(11) DEFAULT 0,
  `description` text DEFAULT NULL,
  `created_at` timestamp NOT NULL DEFAULT current_timestamp()
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

5.CREATE TABLE `users` (
  `user_id` int(11) NOT NULL,
  `name` varchar(100) NOT NULL,
  `email` varchar(150) NOT NULL,
  `phone` varchar(15) DEFAULT NULL,
  `password` varchar(255) NOT NULL,
  `created_at` timestamp NOT NULL DEFAULT current_timestamp()
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

## screenShorts

https://github.com/Pavibritta/Learn-Sql-and-Mangodb/issues/4


