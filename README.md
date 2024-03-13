# github.com/danielsarmientossc/say
## Usage
Initialize your module

```go mod init github.com/danielsarmientossc/say```

## Get the say module
Note that you need to include the v in the version tag.

```go get github.com/danielsarmientossc/say@v0.1.0```


```
package main

import (
    "fmt"

    "github.com/danielsarmientossc/say"
)

func main() {
    fmt.Println(golib.Add(2,3))
    fmt.Println(golib.Subtract(2,3))
}
```
