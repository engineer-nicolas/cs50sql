# CS50 SQL Course - Introduction to Databases with SQL - Harvard University

 **CS50’s Introduction to Databases with SQL** is a course offered by **Harvard University** through the HarvardX and Harvard Extension School programs.
 
For each lecture, I created a Jupyter Notebook containing the most important concepts and exercises covered during the lecture. Each notebook can be viewed and executed in Google Colab, provided that the databases stored in the corresponding lecture folder are uploaded. The only exception is Lecture 6, which must be executed locally, as it requires a local MySQL installation.

---
# Course Content

## Lecture 0 — Querying

This lecture introduces the fundamentals of querying a database using SQL. You learn how to:

- Retrieve data using `SELECT`
- Limit result sets with `LIMIT`
- Filter rows with `WHERE`
- Sort results with `ORDER BY`
- Handle comparisons, Boolean logic, and pattern matching (e.g., `LIKE`)
- Work with `NULL` values and multiple conditions in queries
---

## Lecture 1 — Relating

In this lecture you explore how to work with related data:

- Define and use **primary keys** and **foreign keys**
- Understand relationships between tables
- Write **JOIN** clauses to combine rows across tables
- Use nested queries (subqueries) for complex relations
- Group data with `GROUP BY` and filter groups with `HAVING`

## Lecture 2 — Designing

Lecture 2 focuses on designing a schema with appropriate types and structure:

- Create tables using `CREATE TABLE`
- Choose column types and constraints (`PRIMARY KEY`, `NOT NULL`, etc.)
- Normalize schemas to reduce redundancy
- Modify tables (`ALTER TABLE`)
- Understand how schema choices impact data integrity and query performance

## Lecture 3 — Writing

This lecture covers writing and modifying data in your database:

- Insert new rows using `INSERT`
- Update existing data with `UPDATE`
- Remove rows with `DELETE`
- Clean data or enforce change via conditional updates
- Explore triggers (procedural logic that runs when data changes)

## Lecture 4 — Viewing

Lecture 4 introduces advanced ways to organize and present query results:

- Create **views** using `CREATE VIEW` to simplify complex queries
- Use **aggregate functions** (`SUM`, `COUNT`, `AVG`, etc.)
- Explore common table expressions (CTEs) for modular queries

## Lecture 5 — Optimizing

This lecture examines performance and efficiency in SQL:

- Improve query performance with **indexes** (`CREATE INDEX`)
- Understand indexing structures like B-trees
- Manage concurrency and performance boundaries with transactions (`BEGIN`, `COMMIT`, `ROLLBACK`)
- Explore locking, consistency, and replication concepts

## Lecture 6 — Scaling

The final lecture expands your SQL knowledge to real database servers:

- Compare SQLite with server-based systems (MySQL, PostgreSQL)
- Connect client applications to SQL engines
- Learn about replication, sharding, and distributed data
- Explore access controls and authentication for production systems
- Avoid SQL injections attacks with prepared statements (`PREPARE`)

---

## Projects and Problem Sets

Each lecture is paired with a problem set where you apply the SQL clauses and database concepts learned, such as:

- Writing complex queries across related tables
- Designing schemas for normalized datasets
- Inserting, updating, and deleting data responsibly
- Creating views to faciliate modular data analysis
- Optimizing query performance and understanding real-world scalability issues

## About Harvard University

Harvard University is a private Ivy League research university in Cambridge, Massachusetts known for its rigorous academic programs and global education initiatives. CS50 courses, including CS50 SQL, are taught by Harvard faculty and extended to global learners through online platforms with freely accessible lecture materials and problem sets.

