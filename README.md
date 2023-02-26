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
 
![image](https://user-images.githubusercontent.com/101376775/221355397-d06a4631-2d72-4008-884a-a771c75f4f2a.png)

## Create a pastries table exercise

![image](https://user-images.githubusercontent.com/101376775/221355730-dddda774-51e9-47b2-a6fa-0caa56ac9a2e.png)

## Inserting Data into table and viewing it

![image](https://user-images.githubusercontent.com/101376775/221361523-128c0919-16e8-40f5-aee2-071a39fb2fc9.png)

### Exercise to insert single ,multiple data and view them

![image](https://user-images.githubusercontent.com/101376775/221362164-6a24cc06-db15-4132-9dfc-536137d3145d.png)

### Show warnings

![image](https://user-images.githubusercontent.com/101376775/221363059-b2cd0ad3-1b6a-406a-b072-5feae0dad2f2.png)

## Null
![image](https://user-images.githubusercontent.com/101376775/221363140-01bad219-7b99-4981-abb4-baa24342447b.png)

**Null value is allowed here**

![image](https://user-images.githubusercontent.com/101376775/221363436-35e63dda-167b-4ee6-b3c1-923b121ba0d6.png)

### We can also leave all the fields empty if allowed 
![image](https://user-images.githubusercontent.com/101376775/221363547-63368181-9825-4dd9-be68-3cec0c4a3119.png)

### If we don't want to allow null values 
![image](https://user-images.githubusercontent.com/101376775/221364509-8279d57d-6f7f-44b5-b9fe-b422300b65f1.png)


### If we try to give null value then 
![image](https://user-images.githubusercontent.com/101376775/221364637-78c716be-c387-4456-aa15-994202ad64c1.png)

### We can also set the default value fields
![image](https://user-images.githubusercontent.com/101376775/221365103-40bd3029-2c32-41c3-bf6f-91f2a7790d2f.png)
### Here i have used NOT NULL because we may set NULL manually. 
![image](https://user-images.githubusercontent.com/101376775/221365975-c9b93440-f9e3-415b-9154-a8fa6d84d492.png)

### What is this
![image](https://user-images.githubusercontent.com/101376775/221403677-ebd289c9-2caf-4775-8747-bd7cceabbf68.png)

### as can be seen data can be identical
![image](https://user-images.githubusercontent.com/101376775/221403906-9cd02195-97cc-42c5-8743-9477c1536489.png)

what we can do is provide a **Unique indentifier** to differenceiate between them 
for this we can take use of **Primary key**  and they must be **unique** 


### we have create a table with cat_id as primary key
![image](https://user-images.githubusercontent.com/101376775/221404657-e3488f17-10f2-490b-87fe-498e4455fca3.png)
because of that we have PRI written in key column. 

### write all the key normall and assign the PRIMARY KEY(key)
## AUTO_INCREMENT can also be used. 
![image](https://user-images.githubusercontent.com/101376775/221405344-bee00a75-89de-4383-88a2-e07b8851b327.png)
![image](https://user-images.githubusercontent.com/101376775/221405400-621910df-5f8c-459b-8345-2d28a12fb077.png)

##Exercise PRIMARY KEY , AUTO_INCREMENT 
![image](https://user-images.githubusercontent.com/101376775/221407717-1fe1f57c-1314-4e5f-ae00-70d834d19767.png)

# CRUD BASICS
---







