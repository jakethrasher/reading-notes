#### SQL
* Structured Query Language
* designed for technical and non-technical users
* allows users to query, manipulate and transform data from a 'relational' database
* Using SELECT info FROM source, you can access columns of info. The WHERE keyword sets additional parameters on the query
* DISTINCT keywork discards rows that have a duplicate column value
* sort results in ascending or descending order with ORDER BY clause
* ORDER BY column ASC/DESC


* in SQL, the *schema* describes the structure of each table and the datatypes that each column can contain
* 
Database normalization minimizes duplicate data by breaking down data into pieces and storing it in multiple tables. This improves organization but as the data grows, queries get more complex and performance issues could arise from working with a ton of tables. 
Using JOINS allows us to write a query that combines data from multiple tables. Tables
that share information have a unique identifier, a primary key. INNER JOIN matches rows from the first table and second table with the same key. LEFT JOIN RIGHT JOIN and FULL JOIN are used when tables have asymmetric data.