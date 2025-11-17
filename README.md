# 🌟 First Go Project

[![Go Reference](https://img.shields.io/badge/go-1.x-blue.svg)](https://go.dev/)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

A tiny, beginner-friendly Go project that prints "Hello, World!" to the console — perfect for learning the basics of Go and for testing your Go toolchain.

---

## Table of Contents

- [About](#about)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
   - [Clone](#clone)
   - [Run (quick)](#run-quick)
   - [Build (binary)](#build-binary)
- [Example Output](#example-output)
- [Data Types](#data-types)
- [Notes & Tips](#notes--tips)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About

This repository contains a minimal Go program (test.go) that prints "Hello, World!" to the terminal. It's intentionally small so newcomers can focus on setup, running, and basic Go workflow.

---

## Project Structure

- `test.go` — the main program that prints "Hello, World!"
- `data_types.go` — a new file that demonstrates basic Go data types.

---

## Prerequisites

- Go (Golang) installed. Visit https://go.dev/ and follow the installation instructions for your OS.
- Basic familiarity with running commands in a terminal.

---

## Getting Started

### Clone

Clone the repository and change into the project directory:

```bash
git clone https://github.com/Achintha-999/first-go-project.git
cd first-go-project
```

### Run (quick)

Run the program directly with `go run`:

```bash
go run test.go
```

### Build (binary)

Build a standalone binary and run it:

```bash
go build -o first-go-project test.go
./first-go-project
```

---

## Example Output

When you run the program you should see:

```
Hello, World!
```

---

## Data Types

The `data_types.go` file introduces and demonstrates the following basic data types in Go:

- **Integers**: Whole numbers, e.g., `int`, `int8`, `int16`, `int32`, `int64`.
- **Floating-point numbers**: Numbers with decimals, e.g., `float32`, `float64`.
- **Strings**: Text data, e.g., `"Hello, Go!"`.
- **Booleans**: Logical values, `true` or `false`.

### Example Code

Here is a snippet from `data_types.go`:

```go
package main

import "fmt"

func main() {
      // Integer
      var age int = 25
      fmt.Println("Age:", age)

      // Float
      var pi float64 = 3.14159
      fmt.Println("Pi:", pi)

      // String
      var greeting string = "Hello, Go!"
      fmt.Println("Greeting:", greeting)

      // Boolean
      var isLearning bool = true
      fmt.Println("Learning Go:", isLearning)
}
```

### Output

When you run `data_types.go`, you should see:

```
Age: 25
Pi: 3.14159
Greeting: Hello, Go!
Learning Go: true
```

---

## Notes & Tips

- File name: the current entrypoint is `test.go`. If you prefer a conventional name, you can rename it to `main.go`. Both work — Go looks for package `main` and `func main()` when building/running.
- Add a `go.mod` file if you extend this project to include modules or external dependencies:
   ```bash
   go mod init github.com/Achintha-999/first-go-project
   ```
- Use `gofmt` or `go vet` to format and check code:
   ```bash
   go fmt ./...
   go vet ./...
   ```

---

## Contributing

Contributions are welcome! If you'd like to:

1. Fork the repo.
2. Make your changes (e.g., add examples, rename files to `main.go`, add tests).
3. Open a pull request with a clear description of what you changed and why.

Please keep changes small and focused for easy review.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

Made with ❤️ using Go.

---












