202204290930

# golang variables

The `var` declares a list of variables; as in function argument lists, the type is last.

The statement can be at package or function level.

```go
package main

import "fmt"

var c, python, java bool

func main() {
	var i int
	fmt.Println(i, c, python, java)
}

```

Next: [[golang-variables-initializers]]

---
# References


---
Tags: #note #golang 