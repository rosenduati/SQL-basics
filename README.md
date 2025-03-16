# SQL-basics
+ State and Explain the components of a DBMS(Database Management System)
1. Database Engine: The core service of the DBMS, responsible for storing, retrieving, and managing data in the database. It handles database queries, data updates, and data integrity.
2. Database Schema: Defines the structure of the database, including tables, relationships, and constraints. It serves as a blueprint for how data is organized.
3. Query Processor: Interprets and executes SQL queries. It converts high-level queries (SQL commands) into low-level operations that the database engine can understand and execute.
4. Database Management Software: A software system that enables users to interact with the database. It provides tools for database creation, modification, management, and security.
5. Data Dictionary: Stores metadata about the database, including the structure of the database, the fields in each table, constraints, and user access levels.
6. Transaction Management: Ensures that all database transactions are processed correctly. It supports the ACID (Atomicity, Consistency, Isolation, Durability) properties to maintain data integrity.
7. Security Management: Manages user access control and ensures that only authorized users can access or modify the data in the database.
   
+ What is a relational database? Give 4 examples. A Relational Database is a type of database that stores data in tables with rows and columns. It uses relationships between different tables to organize and manage data efficiently. Tables are linked using keys (such as primary keys and foreign keys).
+ Examples of Relational Databases:

+ MySQL
+ PostgreSQL
+ Oracle Database
+ Microsoft SQL Server
  
2) State and Explain three classifications of SQL?
+ Three Classifications of SQL SQL (Structured Query Language) is classified into three types based on its functionality:
+ DML (Data Manipulation Language): Includes commands used to retrieve, insert, update, and delete data in the database. Examples: SELECT, INSERT, UPDATE, DELETE
+ DDL (Data Definition Language): Includes commands that define the structure of the database, such as creating and modifying tables, schemas, and indexes. Examples: CREATE, ALTER, DROP, TRUNCATE
+ DCL (Data Control Language): Includes commands used to control access to data and manage permissions for users. Examples: GRANT, REVOKE
  
3) What is the difference between a Primary Key and a Foreign Key?
+ A primary key is a unique identifier for a record in a table. It ensures that no two rows in a table have the same value for the primary key. It cannot contain NULL values. Example: student_id in a students table.
+ Foreign Key: A foreign key is a column or a group of columns used to establish a link between the data in two tables. It refers to the primary key of another table. The foreign key ensures referential integrity by restricting the values to only those that exist in the referenced table. Example: student_id in a courses table, referring to the student_id in the students table.

4) What is an Entity-Relationship Diagram?
+ An Entity-Relationship Diagram (ERD) is a visual representation of the structure of a database. It illustrates how entities (such as tables or objects) relate to each other within the database. An ERD includes entities, attributes (properties of entities), and relationships (associations between entities). Entities: Represent objects or concepts (e.g., Student, Course). Relationships: Define how entities interact (e.g., a student enrolls in a course). Attributes: Define properties or characteristics of entities (e.g., student_id, name, course_code).

5) What are the advantages of relational databases?

+ Data Integrity: Enforces data accuracy and consistency through constraints such as primary keys and foreign keys.
+ Flexibility: Supports complex queries using SQL, allowing for versatile data retrieval and manipulation.
+ Security: Provides user authentication and access control to ensure data security.
+ Scalability: Relational databases can handle large amounts of data and can be optimized for performance with indexing and normalization.
+ Data Independence: Allows for the separation of logical data from physical storage, making it easier to manage and modify the structure without affecting the data.

6) State four types of data type used to store data in tables?
+ Integer: Used to store whole numbers. Example: INT, SMALLINT
+ String/Text: Used to store alphanumeric characters or text. Example: VARCHAR, TEXT
+ Date/Time: Used to store date and time values. Example: DATE, DATETIME, TIMESTAMP
+ Float/Decimal: Used to store decimal numbers or floating-point values. Example: FLOAT, DECIMAL

7) What is the purpose of a database management system (DBMS)?
+ The primary purpose of a Database Management System (DBMS) is to provide an efficient, secure, and convenient way to store, manage, and retrieve data. It ensures that the data is organized in a structured manner, maintains integrity, supports concurrent access by multiple users, and provides mechanisms for backup and recovery. A DBMS also enforces data security and user access control, allowing for the management of large amounts of data in a reliable and scalable way.
