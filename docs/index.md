# Module 07 – Functions

**Adam Gibbs**
**8/23/2020**
**IT FDN 130**


## 1.	Explain when you would use a SQL UDF.
```
A SQL User Defined Function (UDF) evaluated an SQL expression set by the sure and returns as result. 
This return can be a single value scalar, or a table. A SQL UDF can me helpful when an expression 
will need to be conducted multiple times or a calculation or aggregation needs to be conducted. 
```

## 2.	Explain are the differences between Scalar, Inline, and Multi-Statement Functions.

```
A Scalar function returns a single value per expression and can be used in SELECT, WHERE, 
HAIVING and GROUP BY. A table function returns arow set instead of a single value. It can 
be called in FROM, JOIN, or SELECT. Tables are similar to Views, but tables allow for 
parameters. An inline table function returns a table that includes the entire query withing 
the RETURN statement. A Multi-Statement Function is more complicated that an inline function 
as it returns a table that has its variables defined and then data inserted into this new 
defined table. Inline tables allow users to perform function on base tables while Multi-statement
Function require you to insert data into them and therefore can not perform calculation from base tables. 
```
© 2020 GitHub, Inc.
