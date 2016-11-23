# go-quine

I wrote a quine in go! It is `129` bytes long.

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
	b := string(96)
	print(p, b, p, b)
}

const p = `package main

func main() {
	b := string(96)
	print(p, b, p, b)
}

const p = `
```
