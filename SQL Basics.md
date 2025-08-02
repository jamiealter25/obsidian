
### Module 0 - Comment
- Use -- double hyphen at the beginning of a line to make it a comment.
```SQL
--This is a comment
```
---
### Module 1 - SELECT
- This selects column from a table.
- Use * asterisk to select all column. 
```SQL
SELECT Column_name, Column_name ...
SELECT *       --To select all column
```
---
### Module 2 - FROM
- To import selected data from a table.
```SQL
SELECT Column_name
FROM table1
```
---
### Module 3 - WHERE
- To add different conditions.
- The result will be shown based of this condition.
- All these (=, !=, <, <=, >, >=) Standard numerical operators can be used.
```SQL
SELECT Movie_Title, Year
FROM Movies
WHERE Year > 2010
```
---
- Use `AND` , `OR` for more complex condition (`num_wheels >= 4 AND doors <= 2`).
- Below are some useful operators (*`for numerical data`*):

| Operator            | Condition                              | SQL Example                     |
| ------------------- | -------------------------------------- | ------------------------------- |
| =, !=, <, <=, >, >= | Standard numerical operators           | `col_name != 4`                 |
| BETWEEN … AND …     | Number is within range (inclusive)     | `col_name BETWEEN 1.5 AND 10.5` |
| NOT BETWEEN … AND … | Number is not within range (inclusive) | `col_name NOT BETWEEN 1 AND 10` |
| IN (…)              | Number exists in a list                | `col_name IN (2, 4, 6)`         |
| NOT IN (…)          | Number does not exist in a list        | `col_name NOT IN (1, 3, 5)`     |
- Below are some useful operators (*`for string data`*):

| Operator   | Condition                                         | Example                                                       |
| ---------- | ------------------------------------------------- | ------------------------------------------------------------- |
| =          | Case sensitive exact string comparison            | `col_name = "abc"`                                            |
| != or <>   | Case sensitive exact string inequality comparison | `col_name != "abcd"`                                          |
| LIKE       | Case insensitive exact string comparison          | `col_name LIKE "ABC"`                                         |
| NOT LIKE   | Case insensitive exact string inequality          | `col_name NOT LIKE "ABCD"`                                    |
| %          | Matches zero or more characters (with LIKE)       | `col_name LIKE "%AT%"` (matches "AT", "ATTIC", "CAT", "BATS") |
| _          | Matches a single character (with LIKE)            | `col_name LIKE "AN_"` (matches "AND", not "AN")               |
| IN (…)     | String exists in a list                           | `col_name IN ("A", "B", "C")`                                 |
| NOT IN (…) | String does not exist in a list                   | `col_name NOT IN ("D", "E", "F")`                             |
### Module 4 - DISTINCT
- To remove duplicates from selected all columns.
```SQL
SELECT DISTINCT Column_name, Column_name
FROM table1
```
---
### Module 5 - ORDER BY
- To order list.
- Use `ASC` , `DESC` to order by ascending or descending.
```SQL
SELECT Roll, Name
FROM Students
ORDER BY Roll ASC
```
---
### Module 6 - LIMIT & OFFSET
- `LIMIT` is used to **show a certain number of rows**.
- `OFFSET` is used to **skip rows from the top**.
```SQL
SELECT Roll, Name
FROM Students 
LIMIT 5  OFFSET 10  
```
---
### Module 7 - Dot (`.`) Notation
- The dot `.` is used to **specify which table a column belongs to**.
- Format: `TableName.ColumnName`
```SQL
SELECT Students.Name, Enrollments.Course 
```
---
### Module 8 - JOINs
- `JOIN` is used to **combine rows from two or more tables**.

**INNER JOIN**
- Shows rows **only when there is a match in both tables**.
```SQL
SELECT Students.Name, Enrollments.Course  
FROM Students  
INNER JOIN Enrollments  
  ON Students.ID = Enrollments.Student_ID 
```
---

**LEFT JOIN (or LEFT OUTER JOIN)**
- Shows **all rows from the left table**, and matched rows from the right table.
- If no match, right table shows `NULL`.
```SQL
SELECT Students.Name, Enrollments.Course  
FROM Students  
LEFT JOIN Enrollments  
  ON Students.ID = Enrollments.Student_ID 
```
---

**RIGHT JOIN (or RIGHT OUTER JOIN)**
- Shows **all rows from the right table**, and matched rows from the left table.
- If no match, left table shows `NULL`.
```SQL
SELECT Students.Name, Enrollments.Course  
FROM Students  
RIGHT JOIN Enrollments  
  ON Students.ID = Enrollments.Student_ID 
```
---

**FULL JOIN (or FULL OUTER JOIN)**
- Shows **all rows when there is a match in one of the tables**.
- If no match, the missing side shows `NULL`.
```SQL
SELECT Students.Name, Enrollments.Course  
FROM Students  
FULL JOIN Enrollments  
  ON Students.ID = Enrollments.Student_ID 
```
---
### Module 9 - IS NULL & IS NOT NULL
- Use `IS NULL` to **check if a column has no value** (empty or missing).
- Use `IS NOT NULL` to **check if a column has a value** (not empty).
```SQL
SELECT Name, Email
FROM Students
WHERE Email IS NULL;   -- shows students without an email`
```
---
### Module 10 - AS (Alias)
- `AS` is used to **give a temporary name (alias) to a column or table** in the result.
```SQL
SELECT Name AS Student_Name, Age AS Student_Age
FROM Students;
```
---
### Module 11 - Expressions (Math & Operations)
- You can do **math or other operations directly in SQL**.
- These can be used in `SELECT`, `WHERE`, and other clauses.
```SQL
SELECT particle_speed / 2.0 AS Half_Speed
FROM Particles;     --The result will show in a column named Half_Speed
```
---
### Module 12 - ABS (Absolute Value)
- `ABS()` is used to **return the absolute (non-negative) value** of a number, removing any negative sign.
```SQL
SELECT ABS(-25) AS Absolute_Value; -- Output: 25`
```
---
### Module 12 - Aggregate Functions
- **Aggregate functions** allow you to **summarize data** across multiple rows. These functions return a **single value** based on a group of rows, unless grouped otherwise using `GROUP BY`.
- If no `GROUP BY` is used, the function runs over **all rows**.
 ```SQL
 SELECT AGG_FUNC(column_or_expression) AS aggregate_description
 FROM mytable
 WHERE constraint_expression;
```

**Common Aggregate Functions:**

|Function|Description|
|---|---|
|`COUNT(*)` or `COUNT(column)`|Counts total rows (or non-NULL values in a column).|
|`MIN(column)`|Returns the **smallest** value in the column.|
|`MAX(column)`|Returns the **largest** value in the column.|
|`AVG(column)`|Calculates the **average** of numeric values.|
|`SUM(column)`|Adds up all numeric values in the column.|
