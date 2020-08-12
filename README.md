
### QUERYING DATA FROM A TABLE : ###
---

- **SELECT c1, c2 FROM t;**
> Query data in columns c1, c2 from a table t.

- **SELECT * FROM t;**
> Query all rows and columns from a table.

- **SELECT c1, c2 FROM WHERE condition;**
> Query data and filter rows from a table.

- **SELECT DISTINCT c1 FROM t WHERE condition;**
> Query distinct rows from a table.

- **SELECT c1, c2 FROm t ORDER BY c1 ASC [DESC];**
> Sort the result set in ascending or descending order.

- **SELECT c1, c2 FROM t ORDER BY c1 LIMIT n OFFSET offset;**
> Skip offset of rows and return the next n rows.

- **SELECT c1, aggregate(c2) FROM t GROUP BY c1;**
> Group rows using an aggregate function.

- **SELECT c1, aggregate(c2) FROM t GROUP BY c1 HAVING condition;**
> Filter groups using HAVING clause.





[NEXT](https://github.com/indeshan/SQL-Cheat-Sheet/blob/master/QueryingFromMultipleTables.md)
