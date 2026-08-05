# SQL-SYLLABUS

# Database Basics

 ## SQL
SQL (Structured Query Language) is a standard language used to communicate with databases.

 # SQL is used to: 
 
       ✅ Create databases and tables

       ✅ Insert data 

       ✅ Retrieve data

       ✅Update data

       ✅Delete data.

▶ Example:

       SELECT * FROM Employees;
#
# DBMS
DBMS (Database Management System) is software used to store, organize, manage, and retrieve data efficiently.

▶ Features:

     ✅ Stores data

     ✅ Updates data

     ✅ Deletes data

     ✅ Retrieves data

     ✅ Provides security.

▶ Examples:

       ✅ MySQL

       ✅ Oracle

       ✅ Microsoft SQL Server

       ✅ PostgreSQL
#
# RDBMS

RDBMS (Relational Database Management System) is a type of DBMS that stores data in the form of tables and establishes relationships between tables.

▶ Features:

         ✅Data is stored in tables.

         ✅Supports Primary Key and Foreign Key.

         ✅Reduces data redundancy.

         ✅Maintains data integrity.

▶Example:

   * Students Table:
    
          Student_ID	       Name
          
            101	             Rahul
            
   * Courses Table
   
            Course_ID	   Student_ID
            
              C01        	101
              
* Here, Student_ID is used to relate the two tables.

#
# SQL vs MySQL

   ## SQL    
    
        ✅SQL is a language.
        
        ✅Used to write queries.
        
        ✅Cannot store data.
        
        ✅Standard query language.   	
 
  ## MySQL
  
       ✅MySQL is database software (RDBMS).
       
       ✅Executes SQL queries.
       
	      ✅Stores data in databases.
       
       ✅One of the most popular RDBMS.


▶ Easy to Remember:

           SQL = Language 
           
           MySQL = Software
#
 # Tables, Rows, Columns
 
▶Example:

       Emp_ID	   Name	   Salary
       
        101	     John	    30000
        
        102    	 David    40000
        
## Table:
A collection of related data.

 ### Example:
  
          Employees 
         
## Row (Record)
A single entry in a table.  

### Example:

     101 | John | 30000
     
## Column (Field)
A category of information.

### Example:

        Emp_ID|Name|Salary
#
# Constraints : 
   ## UNIQUE KEY , PRIMARY KEY , FOREIGN KEY , NOT NULL.

## Primary Key:
Primary Key is a column (or combination of columns) that uniquely identifies each row in a table.
              
#

## Foreign Key
A Foreign Key is a column that connects one table to another. It maintains the relationship between tables.
#
## Unique Key
A UNIQUE Key ensures that all values in a column are different.
#
## NOT NULL
The NOT NULL constraint ensures that a column cannot be empty.
#

# SQL Commands
## DDL (DATA DEFINITION LANGUAGE )
▶ Used to create and modify database objects.

 ✅ CREATE: Creates a new database or table.
 
 ✅ ALTER : Modifies an existing table.
 
 ✅  DROP : Deletes a table permanently.
 
 ✅ TRUNCATE : Removes all rows from a table but keeps the table structure.

## DML (DATA MANIPULATION LANGUAGE)
▶ Used to insert, update, and delete data.

  ✅ INSERT
, UPDATE, DELETE)
DQL (SELECT)

#3. Basic Queries
SELECT
WHERE
DISTINCT
ORDER BY
LIMIT
OFFSET
ALIAS (AS)
#4. Operators
AND, OR, NOT
IN, NOT IN
BETWEEN
LIKE
IS NULL
Comparison Operators (=, >, <, >=, <=, <>)
#5. Functions
COUNT()
SUM()
AVG()
MIN()
MAX()
String Functions
Date Functions
#6. Grouping
GROUP BY
HAVING
#7. Joins
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL JOIN
SELF JOIN
CROSS JOIN
#8. Advanced SQL
Subqueries
CTE (Common Table Expression)
Views
Indexes
Stored Procedures
Triggers
Window Functions (ROW_NUMBER, RANK, DENSE_RANK)
CASE Statement
<img width="512" height="519" alt="Screenshot 2026-08-04 115526" src="https://github.com/user-attachments/assets/9f93ea7c-9c17-4e7e-a746-a8331ea7d97d" />


