# 2-Month Study Plan for DBMS (SQL) (3 Days/Week)

This plan is designed to master SQL and core Database Management Systems (DBMS) concepts over 2 months, studying 1 hour per day, 3 days per week (Monday, Wednesday, Friday), totaling ~24 hours. The schedule is structured for Notion dashboard integration, with weekly topics, learning objectives, tasks, and resources. The plan focuses on SQL (queries, schema design, optimization) and essential DBMS theory (normalization, transactions), with practical exercises and a final project.

## Plan Overview
- **Duration**: 8 weeks, 3 days/week (Mon, Wed, Fri), 1 hour/day.
- **Total Hours**: ~24 hours (3 hours/week × 8 weeks).
- **Structure**: Each week includes theory (videos/articles), practice (SQL queries), and periodic projects. Friday sessions often focus on practice or review.
- **Notion Integration**: Use a table in Notion with columns for Week, Day, Topic, Learning Objective, Tasks, Resources, and Status (e.g., To Do, In Progress, Done).
- **Prerequisites**: Basic computer literacy; no prior SQL/DBMS knowledge required.
- **Goal**: By the end, you’ll be proficient in writing SQL queries, designing databases, understanding normalization, and applying DBMS concepts in a project.

## Weekly Study Plan

### Week 1: Introduction to DBMS and Basic SQL
**Goal**: Understand DBMS basics and write simple SQL queries.
- **Total Hours**: 3 hours
- **Topics**: DBMS Overview, SQL SELECT, Filtering
- **Learning Objectives**:
  - Explain DBMS purpose and relational databases.
  - Write basic SELECT queries with filtering (WHERE).
- **Schedule**:
  - **Monday (1h)**: DBMS Overview
    - Watch: [DBMS Introduction by Gate Smashers](https://www.youtube.com/watch?v=l1k1yDPGaMg) (0:00-0:15).
    - Read: [GeeksforGeeks - DBMS Introduction](https://www.geeksforgeeks.org/introduction-of-dbms-database-management-system-set-1/).
    - Task: Summarize key DBMS components (tables, keys, queries) in Notion.
  - **Wednesday (1h)**: SQL SELECT
    - Watch: [SQL SELECT by freeCodeCamp](https://www.youtube.com/watch?v=7S_tz1z_5I8) (0:00-0:20).
    - Read: [W3Schools - SQL SELECT](https://www.w3schools.com/sql/sql_select.asp).
    - Task: Write 5 SELECT queries on a sample table (e.g., Employees) using [SQLZoo](https://sqlzoo.net/wiki/SELECT_basics).
  - **Friday (1h)**: Filtering with WHERE
    - Read: [W3Schools - SQL WHERE](https://www.w3schools.com/sql/sql_where.asp).
    - Task: Solve 5 WHERE clause problems on SQLZoo (e.g., filter by age, salary).

### Week 2: SQL Joins and Aggregations
**Goal**: Master SQL joins and aggregate functions.
- **Total Hours**: 3 hours
- **Topics**: JOINs, GROUP BY, Aggregate Functions
- **Learning Objectives**:
  - Combine tables using INNER and OUTER JOINs.
  - Use GROUP BY and aggregate functions (COUNT, SUM, AVG).
- **Schedule**:
  - **Monday (1h)**: JOINs
    - Watch: [SQL JOINs by Tech With Tim](https://www.youtube.com/watch?v=9yeOJ0ZMUYw).
    - Read: [W3Schools - SQL JOIN](https://www.w3schools.com/sql/sql_join.asp).
    - Task: Write 3 queries using INNER and LEFT JOIN on sample tables (e.g., Orders, Customers) on [HackerRank SQL](https://www.hackerrank.com/domains/sql).
  - **Wednesday (1h)**: GROUP BY
    - Read: [W3Schools - SQL GROUP BY](https://www.w3schools.com/sql/sql_groupby.asp).
    - Task: Write 3 GROUP BY queries (e.g., count employees by department) on SQLZoo.
  - **Friday (1h)**: Aggregate Functions
    - Watch: [SQL Aggregates by freeCodeCamp](https://www.youtube.com/watch?v=7S_tz1z_5I8) (0:20-0:40).
    - Task: Solve 5 problems using COUNT, SUM, AVG, MIN, MAX on HackerRank.

### Week 3: Advanced SQL Queries
**Goal**: Write complex SQL queries with subqueries and sorting.
- **Total Hours**: 3 hours
- **Topics**: ORDER BY, Subqueries, HAVING
- **Learning Objectives**:
  - Sort query results using ORDER BY.
  - Use subqueries for nested logic.
  - Filter grouped data with HAVING.
- **Schedule**:
  - **Monday (1h)**: ORDER BY
    - Read: [W3Schools - SQL ORDER BY](https://www.w3schools.com/sql/sql_orderby.asp).
    - Task: Write 5 queries using ORDER BY (e.g., sort employees by salary) on SQLZoo.
  - **Wednesday (1h)**: Subqueries
    - Watch: [SQL Subqueries by Telusko](https://www.youtube.com/watch?v=3eRxj9U2J_E).
    - Read: [W3Schools - SQL Subquery](https://www.w3schools.com/sql/sql_subqueries.asp).
    - Task: Write 3 subquery problems (e.g., find employees with above-average salary) on HackerRank.
  - **Friday (1h)**: HAVING
    - Read: [W3Schools - SQL HAVING](https://www.w3schools.com/sql/sql_having.asp).
    - Task: Solve 3 HAVING clause problems (e.g., departments with >5 employees) on SQLZoo.

### Week 4: Schema Design and DDL
**Goal**: Design tables and use Data Definition Language (DDL).
- **Total Hours**: 3 hours
- **Topics**: CREATE, ALTER, DROP, Constraints
- **Learning Objectives**:
  - Create and modify tables using DDL.
  - Apply constraints (PRIMARY KEY, FOREIGN KEY, NOT NULL).
- **Schedule**:
  - **Monday (1h)**: CREATE and DROP
    - Watch: [SQL DDL by freeCodeCamp](https://www.youtube.com/watch?v=7S_tz1z_5I8) (0:40-1:00).
    - Read: [W3Schools - SQL CREATE TABLE](https://www.w3schools.com/sql/sql_create_table.asp).
    - Task: Create a `Students` table with fields (id, name, age) using [DB Fiddle](https://dbfiddle.uk/). Drop it and recreate.
  - **Wednesday (1h)**: ALTER and Constraints
    - Read: [W3Schools - SQL ALTER TABLE](https://www.w3schools.com/sql/sql_alter.asp), [SQL Constraints](https://www.w3schools.com/sql/sql_constraints.asp).
    - Task: Add a PRIMARY KEY and NOT NULL constraint to `Students`. Alter to add a `grade` column.
  - **Friday (1h)**: Practice
    - Task: Design a `Courses` table with a FOREIGN KEY referencing `Students`. Write 3 DDL queries on DB Fiddle.

### Week 5: DML and Transactions
**Goal**: Manipulate data and understand transactions.
- **Total Hours**: 3 hours
- **Topics**: INSERT, UPDATE, DELETE, Transactions
- **Learning Objectives**:
  - Modify data using Data Manipulation Language (DML).
  - Understand transactions and COMMIT/ROLLBACK.
- **Schedule**:
  - **Monday (1h)**: INSERT, UPDATE
    - Watch: [SQL DML by Tech With Tim](https://www.youtube.com/watch?v=9yeOJ0ZMUYw) (0:20-0:40).
    - Read: [W3Schools - SQL INSERT](https://www.w3schools.com/sql/sql_insert.asp), [SQL UPDATE](https://www.w3schools.com/sql/sql_update.asp).
    - Task: Write 5 INSERT and 3 UPDATE queries for `Students` on DB Fiddle.
  - **Wednesday (1h)**: DELETE
    - Read: [W3Schools - SQL DELETE](https://www.w3schools.com/sql/sql_delete.asp).
    - Task: Write 3 DELETE queries (e.g., remove students with age < 18) on SQLZoo.
  - **Friday (1h)**: Transactions
    - Read: [GeeksforGeeks - SQL Transactions](https://www.geeksforgeeks.org/sql-transactions/).
    - Task: Simulate a transaction (INSERT with COMMIT/ROLLBACK) on DB Fiddle.

### Week 6: Normalization and Keys
**Goal**: Learn database normalization and key concepts.
- **Total Hours**: 3 hours
- **Topics**: Normalization (1NF, 2NF, 3NF), Keys
- **Learning Objectives**:
  - Normalize tables to reduce redundancy.
  - Understand primary and foreign keys.
- **Schedule**:
  - **Monday (1h)**: Normalization Basics
    - Watch: [Normalization by Simplilearn](https://www.youtube.com/watch?v=URhQ9h1K2c8).
    - Read: [GeeksforGeeks - Normalization](https://www.geeksforgeeks.org/normalization-process-in-dbms/).
    - Task: Normalize a sample table (e.g., unnormalized student data) to 2NF in Notion.
  - **Wednesday (1h)**: Normalization (3NF)
    - Read: [GeeksforGeeks - 3NF](https://www.geeksforgeeks.org/third-normal-form-3nf/).
    - Task: Continue normalizing the sample table to 3NF. Document in Notion.
  - **Friday (1h)**: Keys
    - Read: [GeeksforGeeks - Keys in DBMS](https://www.geeksforgeeks.org/types-of-keys-in-relational-model-candidate-super-primary-alternate-foreign/).
    - Task: Identify primary and foreign keys in a sample schema (e.g., Library) on DB Fiddle.

### Week 7: Indexes and Query Optimization
**Goal**: Optimize queries using indexes.
- **Total Hours**: 3 hours
- **Topics**: Indexes, Query Optimization
- **Learning Objectives**:
  - Create indexes to improve query performance.
  - Write efficient SQL queries.
- **Schedule**:
  - **Monday (1h)**: Indexes
    - Watch: [SQL Indexes by Telusko](https://www.youtube.com/watch?v=4MLVfsOf6SM).
    - Read: [W3Schools - SQL Indexes](https://www.w3schools.com/sql/sql_create_index.asp).
    - Task: Create an index on a `Students` table column (e.g., name) on DB Fiddle.
  - **Wednesday (1h)**: Query Optimization
    - Read: [GeeksforGeeks - Query Optimization](https://www.geeksforgeeks.org/query-optimization-in-relational-algebra/).
    - Task: Rewrite 3 inefficient queries (e.g., avoid SELECT *) on HackerRank.
  - **Friday (1h)**: Practice
    - Task: Solve 5 advanced SQL problems on HackerRank or SQLZoo, focusing on JOINs and indexes.

### Week 8: Final Project and Review
**Goal**: Build a database project and consolidate knowledge.
- **Total Hours**: 3 hours
- **Topics**: E-Commerce Database Project, Review
- **Learning Objectives**:
  - Design and query a real-world database.
  - Prepare for SQL interviews.
- **Schedule**:
  - **Monday (1h)**: Project Setup
    - Task: Design an E-Commerce database schema (tables: Products, Customers, Orders) with constraints. Create tables on DB Fiddle.
  - **Wednesday (1h)**: Project Queries
    - Task: Write 5 queries for the E-Commerce database (e.g., top 5 products by sales, customer order history).
  - **Friday (1h)**: Review and Interview Prep
    - Task: Solve 5 SQL problems on [LeetCode Database](https://leetcode.com/problemset/database/). Document project on GitHub with a README. Practice 2 interview questions on [Pramp](https://www.pramp.com/).

## Notion Dashboard Setup
1. **Create a Table**:
   - Columns: Week, Day, Topic, Learning Objective, Tasks, Resources (with hyperlinks), Status (To Do, In Progress, Done).
   - Rows: Add entries for each study day (e.g., Week 1, Monday, DBMS Overview).
2. **Track Progress**:
   - Update Status after each session.
   - Add a Notes column for challenges or insights.
3. **Calendar View**:
   - Sync the table with a Notion calendar to visualize study days (Mon, Wed, Fri).
4. **Resources Page**:
   - Create a separate Notion page with all links below for quick access.

## Resources
- **Books**:
  - [SQL in 10 Minutes, Sams Teach Yourself](https://www.pearson.com/us/higher-education/program/Forta-SQL-in-10-Minutes-Sams-Teach-Yourself-5th-Edition/PGM335161.html) by Ben Forta – Quick SQL mastery.
  - [Database System Concepts](https://www.db-book.com/) by Silberschatz, Korth, Sudarshan – DBMS theory (skim for normalization, transactions).
- **Online Courses**:
  - [SQL Tutorial by freeCodeCamp](https://www.youtube.com/watch?v=7S_tz1z_5I8) – Free, comprehensive SQL.
  - [The Complete SQL Bootcamp](https://www.udemy.com/course/the-complete-sql-bootcamp/) (Udemy) – Paid, practical.
- **Tutorials and Articles**:
  - [W3Schools SQL](https://www.w3schools.com/sql/) – Interactive SQL tutorials.
  - [GeeksforGeeks DBMS](https://www.geeksforgeeks.org/dbms/) – Theory and SQL articles.
- **Practice Platforms**:
  - [SQLZoo](https://sqlzoo.net/) – Interactive SQL exercises.
  - [HackerRank SQL](https://www.hackerrank.com/domains/sql) – Query challenges.
  - [LeetCode Database](https://leetcode.com/problemset/database/) – Interview-focused problems.
  - [DB Fiddle](https://dbfiddle.uk/) – Online SQL sandbox for schema design.
- **Interview Prep**:
  - [Pramp](https://www.pramp.com/) – Free peer-to-peer SQL interviews.
  - [SQL Interview Questions](https://www.interviewbit.com/sql-interview-questions/) – Common questions.
- **Tools**:
  - MySQL or PostgreSQL – Install locally or use DB Fiddle.
  - GitHub – Host E-Commerce project (e.g., [ECommerceDB](https://github.com)).

## Tips for Success
- **Consistency**: Stick to the 3-day schedule to build momentum.
- **Active Learning**: Write SQL queries every session, using online sandboxes.
- **Debugging**: Analyze query errors by checking syntax and data.
- **Community**: Join [r/SQL](https://www.reddit.com/r/SQL/) for support.
- **Portfolio**: Document the E-Commerce project on GitHub for job applications.
- **Efficiency**: Focus during the 1-hour sessions; take notes in Notion for quick review.