# gp1

# Getting Started 
1. create github project: https://github.com/robertocamp/gp1
2. cd to your src code directory: `cd ~/Documents/code/go/src`
3. git clone git@github.com:robertocamp/gp1.git
4. `cd gp1`
5. `go mod init github.com/robertocamp/gp1`
6. create main.go
7. basic Hello World code:
```
package main

func main() {
	println("Hello World!")
}
```
8. at this time you are ready to run:
    1. `go run`
    2. `go build`
    3. `go install`

## initial environment verfication
- go run: runs the command in place: `go run main.go`
- go build {main.go}: will build an exectuable *that matches the file name:* `go build main.go`
- go build : will build *a package* in the current directory, *with the name of the parent directory*: `go build`
- $GOPATH: your $GOPATH should contain a `bin` directory ; this is where `go install` will build code
-  `echo $GOPATH`
- go install: will build a binary file in your **$GOPATH/bin** directory: `go install`
- with packages, it is a good idea to keep the package name the same of the parent directory


