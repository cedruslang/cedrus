# Cedrus Programming Language

**Cedrus** is a high-performance, statically typed, compiled programming language designed for simplicity, safety, and speed. Inspired by the expressive syntax of **Rust** and the raw power of **C++**, Cedrus leverages the **Go** toolchain to produce lightweight, native executables.

## 🚀 Key Features

- **Modern Syntax:** Clean, Rust-inspired syntax with `let`, `const`, and `fn` keywords.
- **Strongly Typed:** Catch errors at compile-time with a robust static type system.
- **Compiled Performance:** Transpiles to Go and compiles to native machine code (EXE).
- **Lightweight:** Minimal runtime overhead and fast compilation times.
- **Medium-Level Control:** High-level abstractions with the performance of a systems language.

## 🛠️ Quick Start

### Prerequisites
- [Go 1.22 or higher](https://golang.org/dl/)

### Installation
Clone the repository and build the Cedrus CLI tool:
```bash
git clone https://github.com/youruser/cedrus.git
cd cedrus
go build -o cedrus.exe cmd/cedrus/main.go
```

### Your First Program
Create a file named `hello.ced`:
```rust
fn main() {
    let name: string = "World";
    print("Hello, Cedrus", name, "!");
}
```

### Running & Building
```bash
# Run immediately
./cedrus.exe run hello.ced

# Build a native executable
./cedrus.exe build hello.ced
./hello.exe
```

## 📚 Documentation
For a complete guide on syntax, types, and features, see [DOCS.md](./DOCS.md).

## 🗺️ Roadmap
- [ ] Structs and Custom Types
- [ ] Package/Module System
- [ ] Memory Management Improvements
- [ ] Standard Library Expansion (HTTP, JSON, File IO)

## 📄 License
Cedrus is released under the [Apache 2.0 License](LICENSE).
