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

Function declarations can be shortened when the params share a type:

```go
x int, y int
```

to

```go
x, y int
```



**Notes**: 
- the type comes *after* the variable name.
- Go's declarations read left to right, but C's read in a spiral. *Read more on Reference #2*



---
# References
1. [Go's Declaration Syntax - The Go Programming Language](https://go.dev/blog/declaration-syntax)
2. [Clockwise/Spiral Rule (c-faq.com)](http://c-faq.com/decl/spiral.anderson.html)
3. 

---
Tags: #note #golang