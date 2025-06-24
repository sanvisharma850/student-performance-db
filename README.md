#  Student Performance Database (SQL Project)

This project simulates a simple database to manage and analyze student performance data using SQL. It includes table creation, data insertion, filtering, sorting, and ranking.

##  Tools Used
- SQL (Standard SQL syntax)
- [DB-Fiddle](https://www.db-fiddle.com) for testing

##  Files
- `schema.sql` – Contains table definitions
- `data.sql` – Sample student data using INSERT statements
- `queries.sql` – Practice queries (SELECT, WHERE, ORDER BY, LIMIT, etc.)

##  Example Queries
```sql
-- Get top 3 students by score
SELECT * FROM students ORDER BY score DESC LIMIT 3;

-- List students with score below 60
SELECT * FROM students WHERE score < 60;
