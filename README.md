# Moon Phase 

```go

package main

import (
	"fmt"
	"time"

	"github.com/wahyuhadi/moonphase"
)

func main() {
	m := moonphase.New(time.Now())
	fmt.Println(m.PhaseName())
	fmt.Println(m.IsFullMoon())
	fmt.Println(m.IsNewMoon())
}

```

-- Ramadhan date prediction