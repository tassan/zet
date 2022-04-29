202204290859

# golang functions

Like other languages, functions in `go` can thake zero or more arguments.

```go
package main

import "fmt"

func add(x int, y int) int {
	return x + y
}

func main() {
	fmt.Println(add(42, 13))
}
```

**Note**: the type comes *after* the variable name.



---
# References
[Go's Declaration Syntax - The Go Programming Language](https://go.dev/blog/declaration-syntax)


---
Tags: #note #golang