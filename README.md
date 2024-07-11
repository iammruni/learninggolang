# Learning GoLang

Welcome to my learning repository! This is where I document my journey and store all the materials, projects, and notes related to my learning process. Feel free to explore and learn along with me.

## Install GoLang and Run Your Program

Installing Go is pretty simple. Visit [GoLang Docs](https://go.dev/doc/install) download the binary and install it.

1. To run a 'Hello World' program, create a `main.go` file and write the following program:
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello World!")
}
```
> My interpretation: In Go, all code needs to be in packages. In most languages, the program starts at the `main()` function. In Go, the program starts at the `main()` function in the main package. Separating all files as a package is a good practice.<br/><br/> The imported "fmt" package is an inbuilt Go package which provides I/O like scanf and printf (in C). <br/> <br/> The entry point of the program is the `main()` function. <br/><br/> In Go, exported functions within a package begin with a capital letter, such as `Println()` from the fmt package.
2. Open a terminal and navigate to the path where you've saved the `main.go` file.
    - To directly run: `go run main.go`
    - To build and run: `go build main.go`\
    &nbsp;Windows: `.\main.exe` \
    &nbsp;MacOS: `.\main`
## Resources

1. [Go by Example](https://gobyexample.com/) - A hands-on introduction to Go.
2. [A Tour of Go](https://go.dev/tour/list) - A nice interactive way to learn the basics.

