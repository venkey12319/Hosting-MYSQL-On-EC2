# Hosting-MYSQL-On-EC2


I have provided infrastructure solutions for several clients, who often choose MySQL on EC2 over RDS due to several advantages, such as:

**Full Control and Flexibility**

**Scalability**

**Cost-Effectiveness**

**Data Location Control**

**Easy Migration**

**Handling Larger Database Sizes**

**Meeting Specialized Requirements**

**Custom Networking Configurations**

If you want to set up MySQL on your EC2 instance, follow these steps, and you can have it running within 5 minutes:

Commands to Host MySQL Server on AWS EC2 Instance
Step 1: Update the System

"sudo apt update"

Step 2: Install MySQL

"sudo apt install mysql-server"

Step 3: Check the Status of MySQL (Active or Inactive)

"sudo systemctl status MySQL"

Step 4: Log in to MySQL as Root

"sudo MySQL"

Step 5: Update the Password for the MySQL Server

"ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '123456&';"

"FLUSH PRIVILEGES;"

Step 6: Test the MySQL Server by Running Sample SQL Queries

"CREATE DATABASE mysql_test;"

"USE mysql_test;"

"CREATE TABLE table1 (id INT, name VARCHAR(45));"

"INSERT INTO table1 VALUES (1, 'Venkat1'), (2, 'Venkat2'), (3, 'Venkat3'), (4, 'Venkat4');"

"SELECT * FROM table1;"

Done! Your MySQL server is now set up on EC2.

Choosing between RDS and EC2 for hosting MySQL depends entirely on the application's and client's requirements. Each option has its unique benefits, and the decision should be based on the specific needs of the project.

Feel free to reach out if you have any questions.
