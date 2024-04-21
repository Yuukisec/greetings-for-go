# greetings-for-go

```bash
# 0) 初始化 Go 项目
mkdir go-hello; cd go-hello
go mod init exmaple/hello

# 1) 编写代码 (hello.go)
package main

import (
  "fmt"

  "github.com/yuukisec/greetings-for-go"
)

func main() {
    // Get a greeting message and print it.
    message := greetings.Hello("Gladys")
    fmt.Println(message)
}

# 2) 从本仓库同步依赖
go mod tidy

# 3) 运行项目
go run hello.go
```
