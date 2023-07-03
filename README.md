# go-korea-stock-code

go-korea-stock-code provides a list of stock symbols registered in KRX(Korea Exchange)

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
