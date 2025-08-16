## Common Sequence Formulas in Programming

Below are some of the most common formulas for generating sequences in programming, with explanations and Python implementations.

---

### 1. Arithmetic Sequence
**Formula:** `a_n = start + step * i`

- **Description:** Each term increases by a constant difference (`step`).
- **Example:** 2, 5, 8, 11, ... (start=2, step=3)

```python
start = 2
step = 3
n = 5  # number of terms
for i in range(n):
    print(start + step * i, end=" ")
# Output: 2 5 8 11 14
```

---

### 2. Geometric Sequence
**Formula:** `a_n = start * ratio ** i`

- **Description:** Each term is multiplied by a constant (`ratio`).
- **Example:** 3, 6, 12, 24, ... (start=3, ratio=2)

```python
start = 3
ratio = 2
n = 5
for i in range(n):
    print(start * ratio ** i, end=" ")
# Output: 3 6 12 24 48
```

---

### 3. Odd Numbers Sequence
**Formula:** `a_n = 2 * i + 1`

- **Description:** Generates odd numbers: 1, 3, 5, 7, ...

```python
n = 5
for i in range(n):
    print(2 * i + 1, end=" ")
# Output: 1 3 5 7 9
```

---

### 4. Even Numbers Sequence
**Formula:** `a_n = 2 * i`

- **Description:** Generates even numbers: 0, 2, 4, 6, ...

```python
n = 5
for i in range(n):
    print(2 * i, end=" ")
# Output: 0 2 4 6 8
```

---

### 5. Triangular Numbers
**Formula:** `a_n = i * (i + 1) // 2`

- **Description:** 1, 3, 6, 10, ... (sum of first n natural numbers)

```python
n = 5
for i in range(1, n+1):
    print(i * (i + 1) // 2, end=" ")
# Output: 1 3 6 10 15
```

---

### 6. Square Numbers
**Formula:** `a_n = i ** 2`

- **Description:** 0, 1, 4, 9, 16, ...

```python
n = 5
for i in range(n):
    print(i ** 2, end=" ")
# Output: 0 1 4 9 16
```

---

### 7. Fibonacci Sequence
**Formula:** `a_n = a_{n-1} + a_{n-2}`

- **Description:** 0, 1, 1, 2, 3, 5, ...

```python
n = 6
a, b = 0, 1
for _ in range(n):
    print(a, end=" ")
    a, b = b, a + b
# Output: 0 1 1 2 3 5
```

---

### 8. Factorial Sequence
**Formula:** `a_n = n!`

- **Description:** 1, 1, 2, 6, 24, ...

```python
import math
n = 5
for i in range(n):
    print(math.factorial(i), end=" ")
# Output: 1 1 2 6 24
```

---

These formulas are widely used in pattern problems, mathematics, and programming challenges.
