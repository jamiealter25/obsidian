
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
### Module 4 - FROM
- To import selected data from a table.
```SQL
SELECT Column_name
FROM table1
```
---