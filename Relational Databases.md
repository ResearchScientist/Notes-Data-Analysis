A relational database is a database that contains tables which can form relationships.

Tables contain key and value pairs.

- Primary Key : An identifier that references a column in which each value is unique. 
	One per table.
- Foreign Key :  A field within a table that is a primary key in another table.
	Many per table.

# Normalized Database

Only related data is stored in each table.

# SQL

Structured Query Language

Selects all values. Including duplicates.
```sql
SELECT

FROM

WHERE
```


Selects unique values.
```sql
SELECT
	DISTINCT
```

```sql
INSERT INTO

VALUES
```

```sql
UPDATE

SET
```


# Strings

`SUBSTR()` 

`LENGTH(column)` 

`TRIM(column)` removes whitespace before and after


# Typecast

Change data from one type to another type.

```sql
SELECT
	CAST(column AS FLOAT) -- changes given column to type float --
FROM

WHERE
```

`CONCAT(column1,column2)` concatenates 2 columns
`COALESCE()` returns non null values

