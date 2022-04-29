202204290855

# golang exported names

A package in go will export a name when it has a capital letter.

`Pizza` or `Pi` are exported names and can be used outside their package.

`pizza` and `pi` can't be used outside their package. They're not accessible.

```go
package main

import (
	"fmt"
	"math"
)

func main() {
	fmt.Println(math.pi)
}
```

Running this code will get an error if we don't change `math.pi` to `math.Pi`.

---
# References

---
Tags: #note #golang