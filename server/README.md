# Description
This is a TCP server which can parse HTTP requests
It returns an HTTP repsonse if an HTTP request is sent else it responds with an arbitrary string

It make use of goroutines to handle multiple connections concurrently for scalability and efficiency

# How to use
```bash
# run
go run main.go
```
```bash
# build
go build main.go
./main
```
