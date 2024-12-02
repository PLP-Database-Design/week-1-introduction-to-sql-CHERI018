# SQL Assignment Week 1


## *What You'll Need*
- A computer with internet access.
- A code editor (e.g., Visual Studio Code).
- MySQL Workbench or another SQL database environment.

---



## *Submission Instructions*
1. Answer every question below and put your responses in a file named `answers.md`
2. Push your completed `answers.md` file to your GitHub repository.
3. Submit the GitHub link for review.

---

## **Assignment Questions**

1. State and Explain the components of a DBMS(Database Management System)

2. What is a relational database? Give 4 examples.

3. State and Explain three classifications of SQL?

4. What is the difference between a Primary Key and a Foreign Key?

5. What is an Entity-Relationship Diagram?

6. What are the advantages of relational databases?

7. State four types of data type used to store data in tables?
   
8. What is the purpose of a database management system (DBMS)?  

*How to edit a [markdownfile](https://www.markdownguide.org/basic-syntax/#headings)*

###  NOTE: You should not fork the repository
### 1. Components of a DBMS (Database Management System)
A Database Management System (DBMS) is software that facilitates the creation, management, and manipulation of databases. The main components of a DBMS are:

- **Database Engine**: This is the core service for accessing and managing the data in the database. It ensures data storage, retrieval, and update operations.
- **Database Schema**: A schema defines the structure of the database, including the tables, views, relationships, and other elements.
- **Query Processor**: The query processor interprets and executes SQL commands to retrieve and manipulate data.
- **Database Manager**: This manages the storage, indexing, and retrieval of data. It ensures that data is stored efficiently and can be quickly retrieved.
- **Transaction Manager**: Manages database transactions, ensuring the ACID properties (Atomicity, Consistency, Isolation, Durability) are adhered to.
- **Data Dictionary**: This stores metadata (data about data), including information about the structure of the database and constraints.
- **User Interface**: Provides the interface through which users interact with the DBMS, such as SQL interfaces, GUI tools, or command-line interfaces.

### 2. What is a Relational Database? Give 4 Examples
A **relational database** is a type of database that stores data in tables (also called relations), which are linked to each other by relationships. Data in a relational database is organized into rows and columns, and each table can have relationships with other tables using keys (primary and foreign).

Examples of relational databases:
1. **MySQL**: An open-source relational database management system used for web applications.
2. **Oracle Database**: A widely used enterprise-level relational database system.
3. **Microsoft SQL Server**: A relational database management system developed by Microsoft.
4. **PostgreSQL**: An open-source relational database system known for its advanced features and reliability.

### 3. Classifications of SQL
SQL (Structured Query Language) can be classified into three main categories based on its functionality:

1. **DDL (Data Definition Language)**: Used to define and manage the structure of the database.
   - Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`
   
2. **DML (Data Manipulation Language)**: Used to manipulate and retrieve data from the database.
   - Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`

3. **DCL (Data Control Language)**: Used to control access to data in the database.
   - Examples: `GRANT`, `REVOKE`

### 4. Difference Between a Primary Key and a Foreign Key

- **Primary Key**:
  - A primary key is a field (or a combination of fields) in a table that uniquely identifies each row in that table. 
  - It must contain unique values, and cannot have `NULL` values.
  - Example: In a "Customer" table, `CustomerID` might be the primary key.

- **Foreign Key**:
  - A foreign key is a field (or a combination of fields) in one table that refers to the primary key in another table.
  - It is used to establish and enforce a link between the data in two tables.
  - Example: In an "Order" table, `CustomerID` could be a foreign key that references the `CustomerID` in the "Customer" table.

### 5. What is an Entity-Relationship Diagram?
An **Entity-Relationship Diagram (ERD)** is a visual representation of the entities (objects) in a database and the relationships between them. ERDs are used in the design phase of a database to plan how data will be organized and related. Key components include:
- **Entities**: Represent objects or concepts, such as `Customer`, `Product`, etc.
- **Attributes**: Characteristics of entities, such as `CustomerName`, `ProductPrice`.
- **Relationships**: Define how entities are related to one another, such as "Customer places Order."

### 6. Advantages of Relational Databases
Some key advantages of relational databases include:
1. **Data Integrity**: Relational databases use constraints (e.g., primary and foreign keys) to ensure that data remains consistent and accurate.
2. **Flexibility**: Tables can be modified or extended without affecting existing data.
3. **Normalization**: Relational databases support normalization, which reduces data redundancy and ensures efficient data storage.
4. **Security**: Relational databases support robust security mechanisms, allowing different levels of access control.
5. **Query Power**: SQL allows complex queries to retrieve and manipulate data from one or more related tables.

### 7. Four Types of Data Types Used to Store Data in Tables
Different data types are used to store different kinds of data in database tables. Four common types are:
1. **INT (Integer)**: Used to store whole numbers.
2. **VARCHAR**: Used to store variable-length strings of text.
3. **DATE**: Used to store dates in `YYYY-MM-DD` format.
4. **DECIMAL**: Used to store exact numerical values with a fixed number of decimal places, ideal for financial data.

### 8. Purpose of a Database Management System (DBMS)
The purpose of a DBMS is to provide an efficient, secure, and scalable platform for storing, retrieving, and managing data. A DBMS ensures data consistency, integrity, and accessibility by:
- Managing large amounts of structured data efficiently.
- Allowing multiple users to interact with the data simultaneously without conflicts.
- Providing tools for data manipulation and retrieval through SQL.
- Offering security features to protect data from unauthorized access.
- Supporting transaction management to ensure that database operations are reliable and adhere to ACID properties.
