# SQL

- MySQL can be launched in cloudera Quicstart VM using the following command. 
  ```
  mysql -u root -p cloudera
  ```
  Logging in as `root` gives us ability to create databases in Mysql.
- To display all the available databases use the following command.
  ```
  SHOW DATABSES;
  ```
- To create a database in MySQL use the following command.
  ```
  CREATE DATABASE employees;
  ```
- To display the available tables in the `employees` database first we need to run `USE` command and then `SHOW` command.
  ```
  USE employees;
  SHOW TABLES;
  ```
- To create a tables we use the follwoing command.
  ```
  CREATE TABLE details(id INT, name VARCHAR(20), dept VARCHAR(20), salary INT);
  ```
- To display the format of a table use `DESCRIBE` command.
  ```
  DESCRIBE details;
  ```
- To insert values into the table we use `INSERT INTO` Command.
  ```
  INSERT INTO details VALUES
  (1, 'Alpha', 'Big Data', 2000),
  (2, 'Bravo', 'Sales', 1000),
  (3, 'Charlie', 'HR', 2500),
  (4, 'Delta', 'Big Data', 3000),
  (5, 'Echo', 'Big Data', 5000),
  (6, 'Foxtrot', 'HR', 4500),
  (7, 'Golf', 'HR', 1500),
  (8, 'Hotel', 'sales', 1750),
  (9, 'India', 'Recruiter', 2250),
  (10, 'Juliett', 'Big Data', 2100);  
  ```
