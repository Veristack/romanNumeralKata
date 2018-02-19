# Roman Numeral Kata

The Romans wrote their numbers using letters:
 I = 1
 V = 5
 X = 10
 L = 50
 C = 100
 D = 500
 M = 1000

Rules:
------
- I, X, C, and M can be repeated at most 3 times
- V, L, and D can never be repeated
- I, X, and C (the “1” symbols) can only be subtracted from the next 2 highest values (IV and IX, but not IC)
- Only one subtraction can be made per numeral ('XC' is allowed, 'XXC' is not)
- V, L and D (the “5” symbols) can never be subtracted.

Goal:
-----
Use Test-Driven-Development to write a function which converts arabic to roman numerals.
