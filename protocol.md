# Day 09, 06.02.2025
<span style="color:grey">
</span>

---
## <span style="color:black"> __Basic Overview__ </span>
 

* <span style="color:grey"> Data bases
* <span style="color:grey"> Relational database management system (RDBMS) 
* <span style="color:grey"> example: more practice with python

---
##  __Schedule__
<span style="color:grey">

|Time|Content|
|---|---|
|09:00 - 10:00|Daily review|
|10:00 - 12:00|SQL Exercise notebooks|
|12:00 - 13:00|Lunch break|
|13:00 - 16:00|SQL Exercise notebooks| 
|16:00 - 16:30|Stand up|
|16:30 - 18:00|Exercises and Ending|

---
## <span style="color:black"> __Types of Databases__ </span>
<span style="color:grey">
<span style="color:black"> 1-SQL database (relational databases) features: </span> 
 
A relational database is table-oriented where every bit of data has a link with every other bit of data.It has a row-based table structure which connects related data elements.
* use flexible queries to access data
* use queries that span mutliple tables
* enforce certain constraints on your data
* well documented access language (SQL is ISO standardized)
* examples: PostgreSQL, Mysql, Microsoft SQL Server, Oracle...

 
2-NoSQL database features:
A NoSQL database uses a variety of formats, such as documents, graphs, wide columns, etc, which offers great flexibility and scalability to a database design. 

Note: NoSQL stands for Not Only SQL
* when your access patterns are known beforehand and simple
* when data model fits (facebook connections graph)
* when you need flexible data storage/need to avoid constraints (NoSQL databases are schemaless)
* when you need low latency and easy horizontal scaling (ex: Apple has a 75,000-server NOSQL 
  database!)
* examples: Cassandra, MongoDB, HBase, DynamoDB

![](https://www.kdnuggets.com/wp-content/uploads/williams-sql-nosql-2.jpeg)
---
## <span style="color:black"> __Relational Database Management System (RDBMS)__ </span>

<span style="color:grey">
A relational database management system (RDBMS) is a program that allows you to create, update, and administer a relational database
Most relational database management systems use the SQL language to access the database and run queries
Examples of famous RDBMS are PostgreSQL, MySQL, Oracle, SQLite and Microsoft SQL Server 
 
 ![](https://media.proprofs.com/images/QM/user_images/2503852/New%20Project%20-%202021-11-10T153550_275.jpg)

* Database Server

  
A database server is a computer which uses a DBMS that provides database services to other computers, as defined by the client–server model
Users access a database server through a client program running on the user's computer
To access the database server, you need the following:
the database server's host IP address (a.k.a DB end-point, this can be the local host if the DB is local on our machine)

Username 

Password

Port number (depends on the DBMS)

Database name (because there can be multiple databases on the same server)

 ![](https://nexnetsolutions.com/wp-content/uploads/2021/09/RDBMS.png)
</span>
---


---


---

## <span style="color:black"> __What is SQL ?__ </span> 

SQL stands for Structured Query Language

It allows you access and manipulate relational databases

It became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987

There are different versions/flavors/dialects of the SQL language, depending on the database program used (ex. MySQL, MS Access, Microsoft SQL Server, Orcale)

All versions are very similar in their construction and their support for the main commands

SQL is one of the most important technical skills/tools for a data professional.

Some of THE THINGS IT CAN DO:

SQL can create and delete databases

SQL can create and delete tables in a database

SQL can insert, delete and update records in a database

SQL can retrieve data from a database

SQL can also clean retrieved data before further manipulation (with python for example) to carry out an analysis

Database Structure

A database consists of one/multiple schemas

Schemas consist of tables

Tables consist of columns and rows

A column is a variable and has a unique name

A row is an observation

Every cell is a single value

---

