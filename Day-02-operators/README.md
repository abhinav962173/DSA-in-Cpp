<div align="center">

# 📅 Day 02 — Operators & Type Casting

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Day](https://img.shields.io/badge/Day-02-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**Operators are the verbs of programming. They make things happen.**

</div>

---

## 🧠 What I Learned

> C++ has a rich set of operators — from basic arithmetic to type manipulation.  
> This day covered every major operator type plus how C++ handles type conversions.

---

## 📂 Files Overview

| File | Concept | Description |
|------|---------|-------------|
| `arithmetic_operators.cpp` | Arithmetic | `+`, `-`, `*`, `/`, `%` |
| `assignment_operators.cpp` | Assignment | `=`, `+=`, `-=`, `*=`, `/=`, `%=` |
| `relational_operators.cpp` | Relational | `==`, `!=`, `>`, `<`, `>=`, `<=` |
| `logical_operators.cpp` | Logical | `&&`, `!`, `||` |
| `constant.cpp` | Constants | `const` keyword — values that never change |
| `macros.cpp` | Macros | `#define` — compile-time constants |
| `explicit_type_casting.cpp` | Type Casting | Manual conversion: `(int)3.7` → `3` |
| `implicit_type_casting.cpp` | Type Casting | Auto conversion by compiler |
| `predict_output.cpp` | Practice | Predict what the code outputs before running |

---

## 🔑 Key Concepts

- ✅ All arithmetic, assignment, and relational operators
- ✅ Difference between `const` and `#define`
- ✅ Implicit vs Explicit Type Casting
- ✅ How compiler promotes/demotes data types automatically
- ✅ Output prediction — sharpens logical thinking

---

## 💡 Key Syntax

```cpp
// Arithmetic
int a = 10, b = 3;
cout << a % b;   // Output: 1

// Assignment Shorthand
a += 5;   // a = a + 5

// Relational
cout << (a > b);   // Output: 1 (true)

// Logical 
cout << (5 > 3 && 100 > 90)     // Output: 1 (true)

// Constants
const float PI = 3.14159;
#define MAX 100

// Explicit Type Casting
float x = 3.99;
int y = (int)x;   // y = 3

// Implicit Type Casting
int p = 5;
float q = p;   // q = 5.0 (auto promoted)
```

---

<div align="center">

[⬅️ Day 01 - Variables](../Day-01-variable_and_data_types/README.md) | [⬅️ Back to Main Repo](../README.md)

</div>
