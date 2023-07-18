[![create-pull-request](https://github.com/sunglim/go-korea-stock-code/actions/workflows/create-pull-request.yml/badge.svg)](https://github.com/sunglim/go-korea-stock-code/actions/workflows/create-pull-request.yml)

# go-korea-stock-code

go-korea-stock-code provides a list of stock symbols registered in KRX(Korea Exchange)

Package managed: https://pkg.go.dev/github.com/sunglim/go-korea-stock-code/code

# How to use

```go
import "github.com/sunglim/go-korea-stock-code/code"

...

func Foo() {
   // Prints `005930`
   log.Println(code.Code삼성전자)

   // Prints `삼성전자`
   log.Println(code.CodeToName("005930"))
}
```
