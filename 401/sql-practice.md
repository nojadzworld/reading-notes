# What is SQL?

**SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.**

## Relational databases

**A relational database represents a collection of related (two-dimensional) tables.**

## SELECT

**often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned.**

## WHERE

**The clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.**

## DISTINCT & ORDER BY

**SQL provides a convenient way to discard rows that have a duplicate column value by using distinct**

**most data in real databases are added in no particular column order. As a result, it can be difficult to read through and understand the results of a query as the size of a table increases to thousands or even millions rows.
To help with this, SQL provides a way to sort your results by a given column in ascending or descending order using the ORDER BY claus**

## LIMIT & OFFSET 

**Another clause which is commonly used with the ORDER BY clause are the LIMIT and OFFSET clauses, which are a useful optimization to indicate to the database the subset of the results you care about.
The LIMIT will reduce the number of rows to return, and the optional OFFSET will specify where to begin counting the number rows from.**

## JOINS

**Using the JOIN clause in a query, we can combine row data across two separate tables using this unique key.**

![JOIN](img/JOIN.png)

[SQLBOLT](https://sqlbolt.com/lesson/select_queries_introduction)