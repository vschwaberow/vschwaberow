<h2>Welcome to Volker's bio</h2>
<img align='right' src="https://github-readme-stats.vercel.app/api?username=vschwaberow&show_icons=true&theme=radical" width="380">
<br>
```go
package main

import "fmt"

type Person struct {
    City string
    Country string
    Job string
    Age string
}

func main() {
    volker := &Person {
        City: "Gelsenkirchen",
        Country: "Germany",
        Job: "Something with IT",
        Age: "Youth with home computers at Karstadt"
    }
    fmt.Printf("%#v\n", volker)
}
```
---
