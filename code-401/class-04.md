# Readings: Data Modeling
 
## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?

- SQL databases are good fit for the complex query intensive environment.

2. What type of database is the best fit for hierarchical data storage?

- NoSQL database are the best fit for hierarchical data storage.

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
sql modeling techniques.

- SQL databases are vertically scalable, while NoSQL databases are horizontally scalable. SQL databases are table-based, while NoSQL databases are document, key-value, graph, or wide-column stores. SQL databases are better for multi-row transactions, while NoSQL is better for unstructured data like documents or JSON.

## SQL m0deling techniques


1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

- We connect lines between tables to show relationships.  In some cases an entry in one table can be related to more than one entry in another.  This is called a one-to-many relationship.

2. Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.

- 
3. Explain the difference between a primary and foreign key.

- primary keys uniquely identify each row in a table.
- component key is when the key has combination of multiple columns.


## SQL vs NoSQL

1. How do we treat keywords and parameters differently in SQL syntax?

- they are coomands used for inserting, updating retrieving and deleting data for creating or joining tables.

2. Define normalization within the context of schemas and data.

- normalized schemas is used to avoid storage of duplicate data so that stored data can't become inconsistent.

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- One-to-one: A record in one table is related to one record in another table. 
- One-to-many: A record in one table is related to many records in another table. 
- Many-to-many: Multiple records in one table are related to multiple records in another table.


## Resources
- [The best documentation for  NoSQL vs SQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool) 
- [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
- [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
