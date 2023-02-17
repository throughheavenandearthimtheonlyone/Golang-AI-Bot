# Golang MongoDB CRUD API
This is a project with Golang APIs that access and modify a Mongo database. It can create user data, get and delete them.


## Technologies Used
* Golang
* MongoDB
* Postman

## Dependencies

* Install Go - https://go.dev/doc/install
* Install MongDB - https://www.mongodb.com/docs/manual/installation/
* Install Postman - https://www.postman.com/downloads/


## Executing program
* Download the repository to your computer and go to project file
```
git clone https://github.com/mobenh/Golang-MongoDB
cd Golang-MongoDB
```
* Run code
```
go run main.go
```
* Test APIs with Postman
  * Create a POST request with localhost:9000/user
  * Create a GET request with localhost:9000/user/627aaa45fc70a91c609d1f1e (627aaa45fc70a91c609d1f1e is the ID)
  * Create a DELETE request with localhost:9000/user/627aaa45fc70a91c609d1f1e
