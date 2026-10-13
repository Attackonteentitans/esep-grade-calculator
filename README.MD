# ESEP Grade Calculator

This library calculates a student's weighted final grades based on their assignment, exam, and essay scores throughout the course.

#Runtime requirements:
Golang 1.24 or newer

# Files
"go.mod" go module info
"grade_calculator_test.go" tests to see if calculator works correctly
"grade_calculator.go" code to calculate a student's weighted final grade
"README.MD" info of the library
#Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```