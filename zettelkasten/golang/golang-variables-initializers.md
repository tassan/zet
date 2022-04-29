202204290936

# golang variables initializers

A `var` can include initializers, one per variable and the type can be omitted, so the variable will take the type of the initializer.

```go
package main

import "fmt"

var i, j int = 1, 2

func main() {
	var c, python, java = true, false, "no!"
	fmt.Println(i, j, c, python, java)
}

```


---
# References
1. [[golang-variables]]
---
Tags: #note #golang 