## 📚 Python Lecture 1 & 2 Notes

---

### 🔍 **Internal Working of Python**

#### ✅ **What is Python?**

Python is a **high-level, interpreted programming language** known for its **simplicity** and **readability**. It supports multiple programming paradigms:

- **Procedural Programming**
- **Object-Oriented Programming (OOP)**
- **Functional Programming**

---

### ⚙️ **How Python Works Internally**

#### 🧠 **Python Virtual Machine (PVM)**

- **Definition:** PVM (Python Virtual Machine) is the core part of Python's runtime environment. It **executes bytecode** generated by the Python compiler.

- **Working Process:**  
  1️⃣ Python **source code** (`.py` files) is first **compiled into bytecode** (`.pyc` files) by the Python compiler.  
  2️⃣ This **bytecode is platform-independent** and optimized for faster execution.  
  3️⃣ The **PVM reads and executes bytecode** line-by-line.

---

### 🔄 **Flow of Python Code Execution**

1️⃣ **Write Code:** Create Python code in `.py` files.  
2️⃣ **Compilation:** The Python interpreter converts code into **bytecode**.  
3️⃣ **Execution:** The **PVM** executes the bytecode.

---

### 🗝️ **Key Components**

- **Interpreter:** Converts Python code to bytecode.
- **Compiler:** Optimizes code for better performance.
- **PVM:** Executes the bytecode.

---

## 🇮🇳 **Hinglish Version**

### 🔍 **Python Kya Hai?**

Python ek **high-level programming language** hai jo **simple aur readable** code likhne ke liye famous hai. Yeh programming paradigms ko support karta hai:

- **Procedural Programming**
- **Object-Oriented Programming (OOP)**
- **Functional Programming**

---

### ⚙️ **Python Virtual Machine (PVM)**

- **Definition:** PVM Python ka ek runtime environment hai jo **bytecode ko execute** karta hai.

- **Kaise Kaam Karta Hai:**  
  1️⃣ Python ka **source code** (`.py` files) ko compiler pehle **bytecode** (`.pyc` files) mein convert karta hai.  
  2️⃣ Yeh **bytecode platform-independent** hota hai aur fast execution ke liye optimized hota hai.  
  3️⃣ **PVM bytecode ko line-by-line execute** karta hai.

---

### 🔄 **Python Code Execution Ka Flow**

1️⃣ **Code Likho:** Python code `.py` file mein likho.  
2️⃣ **Compilation:** Interpreter code ko **bytecode** mein convert karta hai.  
3️⃣ **Execution:** Bytecode ko **PVM execute** karta hai.

---

### 🗝️ **Important Components:**

- **Interpreter:** Code ko bytecode mein convert karta hai.
- **Compiler:** Code ko optimize karta hai.
- **PVM:** Bytecode ko execute karta hai.

---

## 📚 **Lecture 2: Numbers in Depth in Python**

### 🔢 **Working with Numbers in Python**

Python supports various numeric types:

- **Integers (int):** Whole numbers like `5`, `100`, `-20`
- **Floating-point (float):** Decimal numbers like `3.14`, `-0.001`
- **Complex Numbers (complex):** Numbers with real and imaginary parts like `3 + 4j`

---

### 🔍 **Internal Working of Numbers**

- **Integers:** Stored as variable-length objects.
- **Floating-point:** Based on the IEEE 754 standard for representing decimals.
- **Complex Numbers:** Represented as a pair of floating-point numbers.

---

### 🧪 **Functions: `repr()`, `str()`, and `print()`**

1️⃣ **`repr('chai')`:** Returns the **string representation** for debugging.

- Example: `repr('chai')` ➜ `'chai'`

2️⃣ **`str('chai')`:** Returns a **readable string** format.

- Example: `str('chai')` ➜ `chai`

3️⃣ **`print('chai')`:** Prints the output to the console.

- Example: `print('chai')` ➜ chai

**Key Difference:**

- `repr()` is for **developers** (debugging purpose).
- `str()` and `print()` are for **users** (readable output).

---

### 📐 **Python Math Library (`math` Module)**

The `math` module provides functions for **mathematical operations**:

- **`math.sqrt(25)`** ➜ Calculates square root (output: `5.0`)
- **`math.factorial(5)`** ➜ Calculates factorial (`120`)
- **`math.pi`** ➜ Returns the value of Pi (`3.14159...`)
- **`math.sin(x)`**, **`math.cos(x)`** ➜ Trigonometric functions

**Importing Math Library:**

```python
import math
print(math.sqrt(16))  # Output: 4.0
```

---

### 🔻 **What is `trunc()`?**

- **Definition:** `trunc()` is used to **truncate the decimal part** of a floating-point number, returning only the integer part.
- **Example:**

```python
# import math
# print(math.trunc(3.99))  # Output: 3
```

- **Use Case:** Similar to `int()` but specifically designed for floating-point truncation.

---

✨ _Yeh notes GitHub pe upload karne ke liye perfectly formatted hain. Koi aur topic ho toh batao!_ 🚀
