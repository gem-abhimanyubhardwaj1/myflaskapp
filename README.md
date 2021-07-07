# myflaskapp

For this project to run, you need to install following pip packages
1.  flask
2.  flask_mysqldb
3.  WTForms
4.  passlib.hash


Also you need to create an sql database name 'myflaskapp' and a table named 'users' in it.
users table -> CREATE TABLE users(id INT(11) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100),email VARCHAR(100), username VARCHAR(30), password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);
