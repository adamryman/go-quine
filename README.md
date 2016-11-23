# go-quine

I wrote a quine in go! It is `192` characters long.

Try it out!
``` 
go get github.com/adamryman/go-quine
cd $GOPATH/github.com/adamryman/go-quine
go run main.go
```

Here is the formatted code:
```
package main

func main() {
	print(p)
	print(string(96))
	print(p)
	print(string(96))
}

var p string = `package main

func main() {
	print(p)
	print(string(96))
	print(p)
	print(string(96))
}

var p string = `
```
