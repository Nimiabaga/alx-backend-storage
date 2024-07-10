# MySQL Advanced

## Description

This project is designed to enhance your understanding of advanced SQL concepts using MySQL. You will learn how to create tables with constraints, optimize queries by adding indexes, and implement stored procedures, functions, views, and triggers in MySQL.

## Learning Objectives

By the end of this project, you should be able to explain and demonstrate the following concepts:

- How to create tables with constraints
- How to optimize queries by adding indexes
- How to implement stored procedures and functions in MySQL
- How to implement views in MySQL
- How to implement triggers in MySQL

## Requirements

- All files will be executed on Ubuntu 18.04 LTS using MySQL 5.7 (version 5.7.30)
- Each file should end with a new line
- Each SQL query should have a comment just before it, explaining the task
- All SQL keywords should be in uppercase (e.g., SELECT, WHERE)
- A `README.md` file at the root of the folder is mandatory
- The length of files will be tested using `wc`

## Resources

- [MySQL cheatsheet](https://devhints.io/mysql)
- [MySQL Performance: How To Leverage MySQL Database Indexing](https://www.digitalocean.com/community/tutorials/mysql-indexing)
- [Stored Procedure](https://dev.mysql.com/doc/refman/5.7/en/create-procedure.html)
- [Triggers](https://dev.mysql.com/doc/refman/5.7/en/triggers.html)
- [Views](https://dev.mysql.com/doc/refman/5.7/en/create-view.html)
- [Functions and Operators](https://dev.mysql.com/doc/refman/5.7/en/functions.html)
- [Trigger Syntax and Examples](https://dev.mysql.com/doc/refman/5.7/en/trigger-syntax.html)
- [CREATE TABLE Statement](https://dev.mysql.com/doc/refman/5.7/en/create-table.html)
- [CREATE PROCEDURE and CREATE FUNCTION Statements](https://dev.mysql.com/doc/refman/5.7/en/create-procedure.html)
- [CREATE INDEX Statement](https://dev.mysql.com/doc/refman/5.7/en/create-index.html)
- [CREATE VIEW Statement](https://dev.mysql.com/doc/refman/5.7/en/create-view.html)

## Concepts Explained

### Creating Tables with Constraints

Learn how to create tables with various constraints such as primary keys, foreign keys, unique constraints, not null constraints, and check constraints to ensure data integrity.

### Optimizing Queries with Indexes

Understand how to create indexes on columns to speed up data retrieval operations and optimize query performance.

### Stored Procedures and Functions

Learn how to encapsulate SQL code into stored procedures and functions, allowing for code reuse and modularity. Procedures and functions help in performing repetitive tasks efficiently.

### Views

Views are virtual tables created by a query. They simplify complex queries, enhance security by restricting access to specific data, and present data in a specific format.

### Triggers

Triggers are procedures that automatically execute in response to certain events on a table or view. They help enforce business rules, validate input data, and maintain an audit trail.

## Usage

### Setting Up the Environment

1. **Start the Container**:
   - Request a container with Ubuntu 18.04 and Python 3.7.
   - Connect via SSH or WebTerminal.

2. **Start MySQL**:
   ```sh
   $ service mysql start

