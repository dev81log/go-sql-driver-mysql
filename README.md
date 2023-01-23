![Asher_Duarte_mixed_elements_code__mysql__golang_3a525d5a-ad83-4f0a-868e-b03e67d51ffa (1)](https://user-images.githubusercontent.com/105469529/213915339-d53e4f8b-fc22-482d-a76f-d0c9648be7da.png)

# Overview
This is a Go program that demonstrates basic CRUD operations on a MySQL database. It connects to a database, performs various queries, and displays the results.

## Dependencies
+ Go
+ MySQL driver for Go ([github.com/go-sql-driver/mysql](url))
+ MySQL database
## Usage
1. Run `go get github.com/go-sql-driver/mysql` to install the MySQL driver
2. Run `go run main.go` to run the program
3. Verify that the program is connected to the database and that the CRUD operations are working correctly
### Note
Make sure to set the enviroment variables for `DBUSER` and `DBPASS`, also the IP and Port for the mysql server where the project will connect.
