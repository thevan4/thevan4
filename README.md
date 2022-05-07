```go
package main

//Me it's me
type Me struct {
	Name   string
	Job    string
	Skills string
}

func main() {
	me := &Me{
		Name:   "Ivan",
		Job:    "Ozon travel core teamlead",
		Skills: "Golang architecture and business problem solving",
	}
	_ = me
}
```
