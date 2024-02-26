# Go-with-Golang
Starting the go language
- It is compiled: read it first then output or intermediate executable file created.
- Go tool can run files directly, without VM.
- Executables are different for OS.
- We can make system as well as web apps - Cloud.
- Object Oriented: Yes and no, what you see on the screen is the code.

## Golang installation and hello World
- Download from : https://go.dev/dl/
- Here i am taking reference of a course so doing exactly like same.
- Create a directory 01hello
- Inside that folder create a file main.go
- Open the terminal set the location at this 01hello directory.
- now load all the tools using: 
    - Recommended:
        
        go mod init github.com/Yourname/hello
    - We will use:
        
        go mod init hello
    - It will give a file go.modgo mod init hello
- Install extension Go in the VS code and click on accept all while installing.
- Come to main.go file and write your first hello world Program:
        
        package main

        func main() {
            fmt.Println("Hello World")
        }
    - We dont have to write import statement for packages, go will automatically handle the import statement.
- run the code:

        go run main.go
    - This will run the file, it will not generate the build file.
        