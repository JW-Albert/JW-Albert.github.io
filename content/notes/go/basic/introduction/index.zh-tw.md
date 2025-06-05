---
title: Go 簡介
weight: 10
menu:
  notes:
    name: 簡介
    identifier: notes-go-basics-intro
    parent: notes-go-basics
    weight: 10
---
<!-- A Sample Program -->
{{< note title="Hello World">}}
以下是一個簡單的 Go 程式範例。
  
```go
package main

import "fmt"

func main() {
  message := greetMe("world")
  fmt.Println(message)
}

func greetMe(name string) string {
  return "Hello, " + name + "!"
}
```

執行程式的方式如下：

```bash
$ go run hello.go
```
{{< /note >}}

<!-- Declaring Variables -->

{{< note title="變數" >}}
**一般宣告方式：**
```go
var msg string
msg = "Hello"
```

**簡短宣告方式：**
```go
msg := "Hello"
```
{{< /note >}}


<!-- Declaring Constants -->

{{< note title="常數" >}}
```go
const Phi = 1.618
```
{{< /note >}}