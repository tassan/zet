202204290943

# golang variables short declarations

Inside a function we can use the `:=` short assignment statement instead of a `var` declaration with implicit type.

Outside a function every statement begins with a keyword (`var`, `function`, etc) and so the `:=` construct is not available.

```go
package main

import "fmt"

func main() {
	var i, j int = 1, 2
	k := 3
	c, python, java := true, false, "no!"

	fmt.Println(i, j, k, c, python, java)
}
```

---
# References
1. [[golang-variables]]
---
Tags: #note #golang 