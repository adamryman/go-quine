# go-quine

I wrote a quine in go! It is `146` characters long.

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
	print(p, string(96), p, string(96))
}

var p string = `package main

func main() {
	print(p, string(96), p, string(96))
}

var p string = `
```
