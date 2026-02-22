
---

# 🧬 Go Generics — Learning Go Type Parameters

A simple Go project demonstrating **generics (type parameters)** introduced in Go 1.18+.  
This repository explores how to write **reusable, type-safe functions and structures** using Go generics.

This project is ideal for understanding **modern Go programming techniques** and how generics improve code reuse, safety, and clarity.

---

## 🎯 Learning Objectives

By working through this project, you will learn:

- What generics are in Go
- How to define type parameters
- How to write generic functions
- How Go enforces type safety at compile time
- When generics are appropriate vs interfaces

---

## 📁 Project Structure

- generics/
  - main.go
  - go.mod
  - README.md

---

## ⚙️ Prerequisites

| Tool | Purpose |
|------|----------|
| Go   | Compiler & runtime |
| Git  | Version control |

---

## 🦫 Installing Go

### Step 1: Check if Go is installed

```bash
go version
```
### Step 2: Install Go (if missing)
``` Linux / macOS:
curl -OL https://go.dev/dl/go1.22.0.linux-amd64.tar.gz
sudo tar -C /usr/local -xvf go1.22.0.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
```
```Windows:
https://go.dev/dl/
```

---

## 🚀 Getting Started
### Step 1: Clone the Repository
```bash
git clone https://github.com/skipajenkins/generics.git
cd generics
```
### Step 2: Install Dependencies
```bash
go mod tidy
```
### Step 3: Run the Program
```bash
go run main.go
```

---

## 🧠 Key Concepts

| Concept              | Explanation                                   |
|----------------------|-----------------------------------------------|
| Generics             | Write functions that work with multiple data types |
| Type Parameters      | Define reusable type placeholders             |
| Type Constraints     | Restrict allowed types                        |
| Compile-Time Safety | Prevent invalid type usage                   |
| Code Reusability     | Reduce duplication                            |


---

## 🏗️ How It Works

1️⃣ Go initializes the module
```bash
go.mod
```
2️⃣ Generic functions are defined
```bash
func Print[T any](value T) { ... }
```
3️⃣ Compiler enforces correctness
```bash
Type checking ensures invalid types never compile.
```
4️⃣ Program executes safely
```bash
go run main.go
```

---

## 🧩 Example Output
```bash
Value: 10
Value: hello
Value: 3.14
```
(Exact output depends on implementation.)

---

## 🧱 Built With

- Go (Golang)

- Go Modules

---

## 📜 License

This project is licensed under the MIT License — free to use, modify, and distribute.

---
