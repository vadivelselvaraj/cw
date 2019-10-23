# Steps to run
- Export the cloudwatch logs to a directory.
- Navigate to `filter` directory and run the below
```
go build -o main main.go
./main -path=logs/a8222e36-56f7-4c4c-bd9f-731786e80a6b > finalOutput.json
gzip finalOutput.json
```