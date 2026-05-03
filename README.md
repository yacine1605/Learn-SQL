this file show how to create tables and reletions between this tables on SQL
Design and implement the database schema for an employee participation information system using SQL. The schema is based on the model developed during the conceptual checkpoint and the relational checkpoint.


Instructions
Understand the Entities and Relationships

Review the details of the system:
  
Employee: Tracks employee information such as number, name, position, salary, and the department they belong to.
Department: Tracks department details, including its number, label, and manager's name.
Project: Tracks project information like number, title, start date, end date, and the department it is assigned to.
Employee Roles in Projects: Tracks the participation of employees in projects, including their roles.
 
Create SQL Tables
les etapes :
1- create Departement&Employee.png
2- create create Project.png

Write SQL scripts to define the following tables:
 
Department
Employee
Project
Employee_Project (for tracking employee roles in projects).
 
Include Primary and Foreign Keys
 
Ensure each table has a primary key to uniquely identify each record.
Define foreign keys to establish relationships between tables, ensuring referential integrity.
Define data types and constraints for all attributes based on the schema:
 Employee Table:

Num_E (Primary Key): INT
Name: VARCHAR(255)
Position: VARCHAR(255)
Salary: DECIMAL(10, 2)
Department_Num_S (Foreign Key): INT
 Department Table:

Num_S (Primary Key): INT
Label: VARCHAR(255)
Manager_Name: VARCHAR(255)
 Project Table:

Num_P (Primary Key): INT
Title: VARCHAR(255)
Start_Date: DATE
End_Date: DATE
Department_Num_S (Foreign Key): INT
Employee_Project Table:

Employee_Num_E (Foreign Key): INT
Project_Num_P (Foreign Key): INT
Role: VARCHAR(255)
3- create create Employer_Project.png
1- create Departement&Employee.png
2- create Project.png 
3- create Employer_Project.png
