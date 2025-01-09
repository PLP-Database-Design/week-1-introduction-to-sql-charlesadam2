1. Components of a DBMS (Database Management System)
A DBMS (Database Management System) is software that manages databases and provides an interface for users to interact with the data. It typically consists of the following components:

Database Engine: The core component responsible for managing the database's storage, retrieval, and update operations.
Database Schema: The structure of the database, which defines how data is organized and related, including tables, views, indexes, and constraints.
Query Processor: This component processes user queries and translates them into commands that the database engine can execute. It interprets SQL statements and executes them efficiently.
Transaction Manager: Ensures that database transactions are processed reliably, maintaining data integrity and handling rollback and commit operations in case of failures.
Data Dictionary: A repository of metadata that describes the database structure, constraints, and other information related to the database schema.
User Interface: Provides the interface for users to interact with the database through commands, forms, reports, etc.
Backup and Recovery Management: Ensures the database can be restored in case of failure, protecting data integrity and availability.
2. What is a Relational Database? Give 4 Examples.
A relational database is a type of database that stores data in tables (also known as relations). Each table contains rows (records) and columns (attributes), and relationships between the tables are established using keys (e.g., primary keys and foreign keys).

Examples of relational databases:

MySQL: An open-source relational database management system.
PostgreSQL: A powerful open-source object-relational database system.
Microsoft SQL Server: A relational database management system developed by Microsoft.
Oracle Database: A multi-model relational database management system produced by Oracle Corporation.
3. Classifications of SQL
SQL (Structured Query Language) can be classified into three categories:

Data Definition Language (DDL): Deals with the structure (schema) of the database. Common commands include:
CREATE: Defines new tables, databases, views, etc.
ALTER: Modifies the structure of an existing table.
DROP: Deletes tables or databases.
Data Manipulation Language (DML): Deals with the manipulation of data within the tables. Common commands include:
SELECT: Retrieves data from the database.
INSERT: Adds new data into a table.
UPDATE: Modifies existing data in a table.
DELETE: Removes data from a table.
Data Control Language (DCL): Deals with permissions and access control. Common commands include:
GRANT: Gives user permissions to access objects.
REVOKE: Removes user permissions.
4. Difference Between a Primary Key and a Foreign Key
Primary Key:
A primary key uniquely identifies each record in a database table.
It cannot accept NULL values.
Each table can have only one primary key.
Example: In a table of students, student_id could be the primary key.
Foreign Key:
A foreign key is a field in a table that links to the primary key of another table.
It establishes a relationship between two tables.
A foreign key can accept NULL values and multiple occurrences of the same value.
Example: In an order table, customer_id could be a foreign key that references the customer_id in the customer table.
5. What is an Entity-Relationship Diagram (ERD)?
An Entity-Relationship Diagram (ERD) is a graphical representation of the entities within a system and their relationships. It visually outlines the structure of a database. Components of an ERD include:

Entities: Represent objects or things within the system (e.g., Customer, Order).
Attributes: The properties or characteristics of an entity (e.g., CustomerName, OrderDate).
Relationships: The associations between entities (e.g., Customer places Order).
Primary Keys: Uniquely identify records in an entity.
Foreign Keys: Used to establish a relationship between two entities.
6. Advantages of Relational Databases
Data Integrity: Relational databases maintain data consistency and integrity using constraints like primary keys, foreign keys, and check constraints.
Flexibility: The ability to handle large volumes of data and adapt to various types of applications.
Normalization: Data redundancy is minimized through normalization, leading to reduced data anomalies.
Scalability: Relational databases can handle large-scale data efficiently, making them suitable for enterprise-level applications.
Security: Access control mechanisms and user permissions help in managing data security.
ACID Properties: Relational databases follow the ACID properties (Atomicity, Consistency, Isolation, Durability) to ensure transactions are processed reliably.
7. Four Types of Data Types Used to Store Data in Tables
Common data types used in relational databases include:

Integer: Used to store whole numbers (e.g., INT, SMALLINT).
Varchar: Used to store variable-length strings (e.g., VARCHAR(255)).
Date/Time: Used to store date and time values (e.g., DATE, DATETIME).
Decimal/Float: Used to store numeric values with decimal points (e.g., DECIMAL(10,2), FLOAT).
8. What is the Purpose of a Database Management System (DBMS)?
The primary purpose of a Database Management System (DBMS) is to provide an efficient, secure, and consistent way to store, retrieve, and manipulate data in a database. Key functions of a DBMS include:

Data Storage Management: Organizing data for efficient storage and retrieval.
Data Retrieval: Providing a querying interface (usually via SQL) to retrieve specific data.
Data Security: Protecting data through user access controls and permissions.
Backup and Recovery: Ensuring data can be restored in case of failure.
Concurrency Control: Allowing multiple users to access and modify the database concurrently without conflict.
Data Integrity: Ensuring that the data is accurate, consistent, and reliable.