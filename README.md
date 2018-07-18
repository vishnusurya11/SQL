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
- To display the available tables in the database first we need to run `USE` command and then `SHOW` command.
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
