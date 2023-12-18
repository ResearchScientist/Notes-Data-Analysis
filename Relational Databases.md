A relational database is a database that contains tables which can form relationships.

Tables contain key and value pairs.

- Primary Key : An identifier that references a column in which each value is unique. 
	One per table.
- Foreign Key :  A field within a table that is a primary key in another table.
	Many per table.

# Providers

- google big query

# Normalized Database

Only related data is stored in each table.

# SQL

Structured Query Language

`SELECT` columns
`FROM` source
`WHERE` filters
`LIMIT` limit number of returned results
`EXTRACT()` 

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

# Joins

Adds null values for any data not matched.
## Inner

Data found in both tables.
## Left

All data from left table and matching data from right table.

## Right

All data from right table and matching data from left table.

## Full

All data from both left and right tables.

```sql
SELECT

FROM

INNER JOIN
	ON
```

# Sub Queries

Nested queries in which the inner query executes before the outer query.

Inside `SELECT`

```sql
SELECT

	(SELECT
	
	FROM ) AS
FROM
```

Inside `FROM`

```sql
SELECT

FROM
(
	SELECT

	FROM

	GROUP BY
)
AS

INNER JOIN

ORDER BY
 DESC
```

Inside `WHERE`

```sql
SELECT

FROM

WHERE
	IN
(
	SELECT

	FROM

	WHERE
)
```


`HAVING` adds filter to query
`CASE` allows if/then statements in query and returns records matching given conditions

```sql
SELECT

CASE

	WHEN
	THEN
	AND
	THEN
ELSE

END AS

FROM

LEFT JOIN

	ON

GROUP BY
```

# Operators

+
-
*
/

```sql
SELECT
	columnA,
	columnB,
	columnA + columnB AS columnC
FROM
	tableA
```

# Aggregate Functions

`SUM` 
`AVG` 
`COUNT()` 

`GROUP BY` groups rows with the same value
`ORDER BY` sorts results, default is ascending (alternate is DESC)

# Temporary Table

`WITH` 
`SELECT INTO` 
`CREATE TABLE` 

