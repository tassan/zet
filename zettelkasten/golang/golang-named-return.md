202204290917

# golang named return

Go can return named values and they're treated as variables defined at the top of the functions.

**These names should be used to document the meaning of the return values**

```go
package main

import "fmt"

func split(sum int) (x, y int) {
	x = sum * 4 / 9
	y = sum - x
	return
}

func main() {
	fmt.Println(split(17))
}

```

A `return` without arguments returns the named return galues aka "naked" return.

**Note:** Naked return statements should be used in short functions.

---
# References
1. [[golang-functions-multiple-results]]


---
Tags: #note #golang