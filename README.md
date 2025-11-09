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

If you'd like help improving this README, or want me to open a pull request that replaces `test.go` with `main.go` and adds a simple `go.mod`, say the word and I can prepare the changes.





