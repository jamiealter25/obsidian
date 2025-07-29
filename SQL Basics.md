
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
