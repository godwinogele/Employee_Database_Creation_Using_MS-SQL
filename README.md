# Employee_Database_Creation_Using_MS-SQL
This repository contains SQL statements to set up a new database called "Employee_Database" and create two tables, "Employee_Details" and "Employee_Salary," for managing employee information.

# Creating a New Database
To create a new database named "Employee_Database," you can use the following SQL statement:

CREATE DATABASE Employee_Database;

# Creating Employee and Salary Tables
After creating the database, you can use it and create the required tables. The following SQL statements demonstrate how to create the "Employee_Details" and "Employee_Salary" tables:

# Using the Database
Before creating tables, ensure you're using the "Employee_Database" with the following SQL statement:

USE Employee_Database;

# Employee_Details Table
To create the "Employee_Details" table with columns for EmployeeID, FirstName, LastName, Age, and Gender, use this SQL statement:

CREATE TABLE Employee_Details
(
	EmployeeID INT,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Age INT,
    Gender VARCHAR(50)
);

# Employee_Salary Table
To create the "Employee_Salary" table with columns for EmployeeID, JobTitle, and Salary, use the following SQL statement:

CREATE TABLE Employee_Salary
(
    EmployeeID INT,
    JobTitle VARCHAR(50),
    Salary INT
);


These SQL statements will set up the "Employee_Database" and create the necessary tables for managing employee details and salaries. You can now insert, update, and retrieve data within these tables as needed for your project.
