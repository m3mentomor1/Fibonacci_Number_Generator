# Fibonacci Number Generator

### 🧐 I. Overview
This is a simple fibonacci number generator that takes an integer input from a user, then uses that input as the term of the fibonacci number to be generated. This program utilizes recursion and memoization (caching) to efficiently compute Fibonacci numbers.

----------------------

### 📦 II. Dependencies
- **functools** - this module is used for the lru_cache decorator that is applied to the recursive function f(n). This decorator caches computed Fibonacci numbers, improving efficiency by avoiding redundant computations. It stores recent function calls and reuses results for the same inputs.
