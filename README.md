# Mysql

## What is a Database

- A structured set of computerized dhat with an accessible interface.
- It's a collection of data
- It's also have methods of accessing and manipulation of that data. 
- For example phone book.
---

## SQL

- SQL stands for structured query language 
- It's the language we use to "talk" to our database

## Some basic MySQL commands 

- **CREATE DATABASE** :- for creating database.
- **DROP DATABASE database name** :- for deleting database .
- **USE DATABASE** :- for useing the database. 
- **SHOW DATABASES** :- for showing all the database we have. 
- **SELECT DATABASE()** :- for knowing what database I am using   
- ** SHOW TABLES** :- show all the tables in cat_app;
- **SHOW COLUMNS FROM table name** 
- **DESCRIBE table name** :- to see the data 
## Types of data 
**Numberic Types**
- INT (whole number with max value of 4294967295.)
- DECIMAL
- NUMERIC
- BIT etc..

**String Types**
- CHAR
- VARCHAR (string of length between 1 and 255, so when we define it we have to also define the max characters varchar(40))
- TEXT 
- ENUM etc...

**Date Types**
- DATE
- DATETIME
- TIMESTAMP etc...

---
## General format for creating table in mysql
> `CREATE TABLE tablenames (tablename should be plural) ` 
> `(`
>    `column_name data_type,`
>   `column_name data-type`
> `)`
 
1:45

### Example 
 CREATE TABLE cats
 (
  name VARCHAR(100),
  age INT
 )
 
 ![image](https://user-images.githubusercontent.com/101376775/221355188-3601a52a-02f3-411f-a978-19a643cf6bf6.png)







