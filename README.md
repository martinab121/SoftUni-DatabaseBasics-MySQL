# Database Basics – MySQL – SoftUni (2020)

Solutions to the exercises and past exams of the **Databases Basics – MySQL** course at [SoftUni](https://softuni.bg).

Each topic is a single plain-text file (no extension) containing the SQL for that lesson's tasks, one after another, each headed by its task number (`1.`, `2.`, ...).

## Topics

| Topic | What it practises | Tasks |
|---|---|---:|
| [Data Definition and Data Types - Exercise](Data%20Definition%20and%20Data%20Types%20-%20Exercise) | `CREATE`/`ALTER`/`DROP` tables, data types, constraints, inserts | 21 |
| [Basic CRUD - Exercise](Basic%20CRUD%20-%20Exercise) | `SELECT`, `WHERE`, `ORDER BY`, `INSERT`, `UPDATE`, `DELETE`, views | 24 |
| [Built-in Functions - Exercise](Built-in%20Functions%20-%20Exercise) | String, date and math functions | 16 |
| [Data Aggregation - Exercise](Data%20Aggregation%20-%20Exercise) | `GROUP BY`, `HAVING`, aggregate functions | 19 |
| [Table Relations - Exercise](Table%20Relations%20-%20Exercise) | Primary/foreign keys, one-to-many and many-to-many relations | 6 |
| [Subqueries and JOINs - Exercise](Subqueries%20and%20JOINs%20-%20Exercise) | `INNER`/`LEFT` joins and subqueries | 16 |
| [Database Programmability - Exercise](Database%20Programmability%20-%20Exercise) | Stored procedures, functions, transactions, triggers | 16 |
| [Databases MySQL Exam - 24 Jun 2017](Databases%20MySQL%20Exam%20-%2024%20Jun%202017) | Past exam – DDL, DML, queries, procedures | 16 |
| [Databases MySQL Retake Exam - 03 Sept 2017](Databases%20MySQL%20Retake%20Exam%20-%2003%20Sept%202017) | Past exam – DDL, DML, queries, procedures | 16 |
| [Database Basics MySQL Exam - 25 February 2018](Database%20Basics%20MySQL%20Exam%20-%2025%20February%202018) | Past exam – DDL, DML, queries, procedures | 15 |
| [Database Basics MySQL Exam - 21 October 2018](Database%20Basics%20MySQL%20Exam%20-%2021%20October%202018) | Past exam – DDL, DML, queries, procedures | 16 |
| [Database Basics MySQL Exam - 9 June 2019](Database%20Basics%20MySQL%20Exam%20-%209%20June%202019) | Past exam – DDL, DML, queries, procedures | 11 |
| [MySQL Retake Exam - 30 July 2019](MySQL%20Retake%20Exam%20-%2030%20July%202019) | Past exam – DDL, DML, queries, procedures | 11 |
| [MySQL Exam - 9 February 2020](MySQL%20Exam%20-%209%20February%202020) | Past exam – DDL, DML, queries, procedures | 11 |
| [Databases MySQL Exam Preparation I](Databases%20MySQL%20Exam%20Preparation%20I) | Exam preparation – full exam-style task set | 18 |
| [Databases MySQL Exam Preparation II](Databases%20MySQL%20Exam%20Preparation%20II) | Exam preparation – full exam-style task set | 18 |

**Total: 250 solved tasks.**

## How to run

1. Create or import the database used by the lesson/exam (SoftUni provides the schema for most exercises, e.g. `soft_uni`, `geography`, `gringotts`).
2. Copy the SQL below a task number into **MySQL Workbench** and execute it, or run it from the `mysql` CLI:

```bash
mysql -u <user> -p <database> < task.sql
```

## Tech

MySQL (DDL, DML, joins, subqueries, aggregation, stored procedures, functions, triggers)
