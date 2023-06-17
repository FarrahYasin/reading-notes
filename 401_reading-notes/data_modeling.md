# Readings: Data Modeling


**<span style="color:red">Data Modeling💻📒</span>**

____________________________________

### nosql vs sql:

**1.** What type of database is the best fit for the complex query intensive environment?
The suitable for complex query-intensive environments is **SQL** database(Structure query language).

NOSQL database is not suitable for complex query-intensive environments because it dose not has a spacific standard interfaces to do a complex queries.

**2.** What type of database is the best fit for hierarchical data storage?
NoSQL databases

**3.** Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

**SQL databases** has ability to (vertically scalable ), that mean we can manage the increasing load by add a lot of things such as,increase the RAM, CPU, SSD...on one single server onley.

**NOSQL databases** has ability to (horizontally scalable), that mean we can add more than one server in our NOSQL databases infrastructure to deal with the huge traffic.
__________________________________

### sql modeling techniques:

**1.** Among data tables, what is a one-to-many relationship and how do we “relate” them?

**one-to-many relationship** mean when an entry in one table can be related to more than one entry in another. 
this is an example for one-to-many relationship -> if we have many books in one library. We see this relationship by connecting lines between the tables to know that we have a one-to-many relationship between these tabels.

**2.** Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

Before designing the relational database, it might be useful to **create** a **diagram** of the database tables and their relationships.

**3.** Explain the difference between a primary and foreign key.
**A primary key:** is a column or set of columns that uniquely identify each row in the table. in the table usually we have only one primary key but we can have more than one.

**A foreign key:** is a column or set of columns that match a primary key in another table. The match between foreign keys and primary keys is what makes a relationship between them.
__________________________________

### sql vs nosql:

**1.** How do we treat keywords and parameters differently in SQL syntax?
**keywords:** have a specific meaning thia keywords is reserved words, keywords use to define the structure of the query, we can't use this keywords in tables names or column names.
**Parameters:** are values that are passed to a query at runtime, parameters is used to define behavior of the query or  to do filter data.

**2.** Define normalization within the context of schemas and data.
**Normalization:** It includes create the tables and establishing relationships between these tabels to reduce 
redundancy and to improve data integrity, so Normalization is a process of organizing the data in a database. 

**3.** Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

**One-to-One Relationship:** 
Each record in one table is related to only one record in another table.
example:A department has one manager and a manager manages one department.

**One-to-Many Relationship:**
Each record in one table can be related to multiple records in another table.
An employee works for one company, and a company has many employees working for it.

**Many-to-Many Relationship:** Entries in both tables can be related to multiple entries in each other.
example:An employee works on many projects, and a project has many employees working on it.
__________________________________

## Things I want to know more about:

I want to know more about SQL & NOSQL😊
