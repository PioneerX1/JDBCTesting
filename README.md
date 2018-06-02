# JDBCTesting
java app to demonstrate JDBC with a MySQL db

While the main java class is relatively straight forward, this requires certain configurations for your MySQL database setup.

## MySQL requirements:
1. a username of 'root' and password 'Connect1234'
2. GRANT ALL PRIVILEGES to this username and password (do this in MySQLWorkbench or MySQL shell)
3. create a database called EMP
4. create a table called Employees(id int not null, age int not null, first varchar(255), last varchar(255));
5. you also need MySQL-connector-java bin jar, and place it on your CLASSPATH, otherwise the Driver won't register.
