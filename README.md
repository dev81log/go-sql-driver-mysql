Overview
This is a Go program that demonstrates basic CRUD operations on a MySQL database. It connects to a database, performs various queries, and displays the results.

Dependencies
Go
MySQL driver for Go (github.com/go-sql-driver/mysql)
MySQL database
Usage
Run go get github.com/go-sql-driver/mysql to install the MySQL driver
Run go run main.go to run the program
Verify that the program is connected to the database and that the CRUD operations are working correctly
Note
Make sure to set the enviroment variables for DBUSER and DBPASS, also the IP and Port for the mysql server where the project will connect.
