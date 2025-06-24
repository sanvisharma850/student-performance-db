# 🎓 Student Performance Database (SQL Project)

This is a beginner-to-intermediate level SQL project that simulates a simple database to manage and analyze student performance using SQL.

## 🔧 Tools Used
- SQL (Standard SQL syntax)
- [DB-Fiddle](https://www.db-fiddle.com) – for testing queries online

## 📁 Files
- `schema.sql` – Table creation (with PRIMARY KEY & NOT NULL)
- `data.sql` – Sample dataset with `INSERT INTO` statements
- `queries.sql` – Query file with common SELECT, WHERE, ORDER BY, LIMIT operations

## 📊 Sample Queries
```sql
-- Top 3 students by score
SELECT * FROM students ORDER BY score DESC LIMIT 3;

-- Students who failed
SELECT * FROM students WHERE score < 60;

