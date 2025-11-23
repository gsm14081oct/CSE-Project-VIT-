A Python library featuring a collection of number theory functions and integer sequence tools. This library provides utilities for factorials, prime factorization, sequence detection, primality tests, modular arithmetic, and special number checks. It's designed for mathematics enthusiasts, students, and programming contest participants.

## Features

- Factorial calculation
- Palindrome checks
- Mean and digital root of digits
- Abundant, deficient, Harshad, automorphic, pronic numbers, and more
- Prime factorization and count
- Prime power and Mersenne prime detection
- Generation of twin primes and Lucas sequences
- Divisor counting, aliquot sums, amicable numbers, and multiplicative persistence
- Highly composite, modular exponentiation, modular inverse, and Chinese Remainder Theorem (CRT)
- Quadratic residue and multiplicative order
- Fibonacci and Carmichael number checks
- Miller-Rabin primality test and Pollard-Rho factorization
- Zeta function approximation and integer partition function
- Polygonal numbers and Collatz sequence steps

## Installation

Simply copy the Python functions into your project, or save them as a `.py` file to import.

```bash
# Example
cp number_theory_utils.py my_project/
```

## Usage Example

Here's how you can use some of the functions:

```python
from number_theory_utils import *

print(factorialn(5))                # 120
print(ispalindromen(121))           # True
print(meanofdigitsn(1234))          # 2.5
print(digitalrootn(9876))           # 3
print(isabundantn(12))              # True
print(primefactorsn(100))           # [2, 2, 5, 5]
print(collatzlengthn(13))           # 9

# Lucas sequence
print(lucassequencen(5))            # [2, 1, 3, 4, 7]

# Chinese Remainder Theorem
print(crtremaindersmoduli([2, 3, 2], [3, 5, 7])) # 23
```

## Function Reference

Each function is self-contained. Parameters generally represent integers for testing properties or extracting sequences.

- `factorialn(n)` – Returns $$ n! $$
- `isabundantn(n)` – Checks if $$ n $$ is abundant
- `primefactorsn(n)` – Returns a list of prime factors of $$ n $$
- `lucassequencen(n)` – Gives first $$ n $$ terms of the Lucas sequence
- `modexp(base, exponent, modulus)` – Computes modular exponentiation
- See the code comments for details on all available functions.

## Contributing

Contributions and improvements are welcome! Please open an issue or pull request.
