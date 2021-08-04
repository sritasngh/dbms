Database is a collection of related data in an organised format.<br>
Relational datatbase management system examples are MySQL, MS Access, Oracle, Sybase, Informix, Postgres. All the database management system use SQL as their standard language. So SQL is used in programming and designed for managing data held in a relational database management system. <br>

Commands
----------------------------------------------------------------------------------------------------------------------------------------

<h4> start MySQL monitor </h4>
 
~~~sql
sudo mysql -u root
~~~

<h4> create a database </h4> 

~~~sql
CREATE DATABASE <name of the database>; 
~~~

<h4> list available databases </h4>

~~~sql
SHOW DATABASES;
~~~

<h4> drop databases </h4>

~~~sql
DROP DATABASE <name of the database>; 
~~~

<h4> Using a database </h4>

~~~sql
USE <name of the database>; 
~~~

<h4> show the name of current database </h4>

~~~sql
SELECT DATABASE(); 
~~~

Tables
----------------------------------------------------------------------------------------------------------------------------------------
Table holds data(related data) and databases are bunch of tables.

Data Types
---------------------------------------------------------------------------------------------------------------------------------------
creating a table, we have to specify the data type of components(fields/columns) in the table. <br>
In mysql following datatypes are there:
<ul>
<li> INT : whole number
<li> VARCHAR : variable length stringh
</ul>

Creating Tables
------------------------------------------------------------------------------------------------------------------------------------------



Primary Key
--------------------------------------------------------------------------------------------------------------------------------------------
It is an unique identifier for a row of table. 

Online editor for SQL 
--------------------------------------------------------------------------------------------------------------------------------------------
[w3 school](https://www.w3schools.com/sql/trysql.asp?filename=trysql_op_or)


psql
===============================================================================================================================

Describe table in psql
------------------------------------------------------------------------------------

```sql
\d+ tablename
```

Resources
---------------------------------------------------------------------------------------------------------------------------------------------
https://www.udemy.com/course/the-ultimate-mysql-bootcamp-go-from-sql-beginner-to-expert/learn/lecture/6914108#questions/3002798
