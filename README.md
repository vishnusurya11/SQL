# SQL

- MySQL can be launched in cloudera Quicstart VM using the following command. 
  ```
  mysql -u root -p cloudera
  ```
  Logging in as `root` gives us ability to create databases in Mysql.
  
 
- To create a database in MySQL use the following command.
  ```
  CREATE DATABASE employees;
  ```
- To display the available tables in the database first we need to run `USE` command and then `SHOW` command.
  ```
  USE employees;
  SHOW TABLES;
  ```
