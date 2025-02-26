---
Title: "MAX()"
Subjects:
  - "Data Science"
  - "Computer Science"
Tags:
  - "SQLite"
  - "PostgreSQL"
  - "MySQL"
  - "function"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-sql"
  - "https://www.codecademy.com/learn/paths/analyze-data-with-sql"
---

## Definition 

The `MAX()` aggregate function takes the name of a column as an argument and returns the largest value in a column.

## Syntax

```sql
SELECT MAX(column_name)
FROM table_name;
```

The opposite of `MAX()` is `MIN()`.

## Example

For instance, suppose there's an `transactions` table with the following values:

| date | amount | 
| -- | -- |
| 2023-01-30 | 2.75 |
| 2023-01-31 | 6.00 |
| 2023-01-31 | 4.20 |

The given query will return the largest value from the `amount` column:

```sql
SELECT MAX(amount) 
FROM transactions;
```

The result would be:

| MAX(amount) | 
| -- |
| 6.00 |
