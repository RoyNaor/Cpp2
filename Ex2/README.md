# SquareMat – Matrix Operations in C++
---

## 📁 Project Structure

```
Ex2/
├── Makefile               # Standard Makefile with multiple build targets
├── SquareMat.h            # Header file for SquareMat class
├── SquareMat.cpp          # Implementation of SquareMat methods
├── test_SquareMat.cpp     # Unit tests using doctest
├── main.cpp               # (Optional) Main demo file
```

---

## 📐 Features

The `SquareMat` class provides:

### 🔢 Matrix Arithmetic
- `+`, `-` between matrices
- Scalar `*`, `/` and `-` unary negation
- Modulo operator `%` with scalar or element-wise matrix

### 🔁 Matrix Utilities
- Transpose with `~`
- Determinant with `!`
- Matrix exponentiation with `^`

### 🔄 In-place Operations
- `+=`, `-=`, `*=`, `/=`, `%=` with matrices or scalars

### 📏 Comparison Operators
- `==`, `!=`, `<`, `<=`, `>`, `>=` (by sum of elements)

### 🔧 Extra Features
- Pre/post increment `++` and decrement `--`
- Bounds-checked access via `operator[]`
- Determinant calculation using recursive minors

---

## 🧪 Unit Tests

Tests are written with [doctest](https://github.com/doctest/doctest). Each core functionality is tested, including:

- Construction, copy, assignment
- Arithmetic operations
- Matrix multiplication & power
- Transpose & determinant
- Scalar operations
- Exception handling for out-of-range access

To run tests:
```bash
make test
```

---

## 🛠️ Build Instructions

You can build the project using either `Makefile` or `CMake`.

### Option 1: Makefile

#### Build:
```bash
make
```

#### Run tests:
```bash
make test 
```

#### Run main:
```bash
./main
```

#### Memory check with Valgrind:
```bash
make valgrind
```

#### Clean artifacts:
```bash
make clean
```

---

## ✅ Requirements

- C++11 or higher
- [doctest](https://github.com/doctest/doctest) (already included)
- Optional: `valgrind` for memory checks

---

## 👨‍💻 Author

**Roy Naor**  
📧 roynaor10@gmail.com  
🔗 [GitHub Repo](https://github.com/RoyNaor/Cpp2)

---
