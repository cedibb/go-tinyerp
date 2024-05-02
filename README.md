# go-tinyerp

**NOTE: This project is currently a Work in Progress (WIP).**

`go-tinyerp` is a Go client library for the Tiny ERP web-based API. This library provides a simple and efficient way to interact with Tiny ERP from your Go applications.

## Installation

To install `go-tinyerp`, you need to install Go and set your Go workspace first.

1. Download `go-tinyerp`: `go get github.com/yourusername/go-tinyerp`
2. Import it in your code: `import "github.com/yourusername/go-tinyerp"`

## Usage

Here's a basic example of how to use `go-tinyerp`:

```go
package main

import (
    "fmt"
    "github.com/cedibb/go-tinyerp"
)

func main() {
    client := gotinyerp.NewClient("your-api-key")
    // use the client
}
