202204290915

# golang functions multiple results

A function can return any number of results

The `swap` functions returns two strings.

```go
package main

import "fmt"

func swap(x, y string) (string, string) {
	return y, x
}

func main() {
	a, b := swap("hello", "world")
	fmt.Println(a, b)
}
```

Next: [[golang-functions-multiple-results]]

---
# References
1. [[golang-functions]]
2. 
---
Tags: #note #golang 