# Common Integer Operations in DSA

1. **Get last digit:**  
   `n % 10`

2. **Remove last digit:**  
   `n // 10` (integer division)

3. **Get number of digits:**  
   `len(str(n))` or `int(math.log10(n)) + 1` (for n > 0)

4. **Reverse an integer:**  
   ```python
   rev = 0
   while n > 0:
       rev = rev * 10 + n % 10
       n //= 10
   ```

5. **Check if a number is even/odd:**  
   `n % 2 == 0` (even), `n % 2 != 0` (odd)

6. **Sum of digits:**  
   ```python
   total = 0
   while n > 0:
       total += n % 10
       n //= 10
   ```

7. **Product of digits:**  
   ```python
   prod = 1
   while n > 0:
       prod *= n % 10
       n //= 10
   ```

8. **Swap two numbers (Python):**  
   `a, b = b, a`

9. **Check if a number is a power of 2:**  
   `n > 0 and (n & (n - 1)) == 0`

10. **Count set bits (number of 1s in binary):**  
    `bin(n).count('1')`

11. **Extract i-th digit from right (0-based):**  
    `(n // (10 ** i)) % 10`

12. **Check if a number is palindrome:**  
    Compare `str(n)` with `str(n)[::-1]`

13. **Find GCD and LCM:**  
    - GCD: `math.gcd(a, b)`
    - LCM: `(a * b) // math.gcd(a, b)`

14. **Check divisibility by 9:**  
    Sum of digits is divisible by 9

15. **Check if a number is prime:**  
    Trial division up to `sqrt(n)`

---
