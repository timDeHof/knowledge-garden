---
id: jvbizumwgycchvyh28nofel
title: Numbers
desc: ''
updated: 1664976331289
created: 1664934306660
---

Python's 2 main types is [[int(integers)|programming-languages.python.data-types.numbers.int]] and [[float(floating point numbers)|programming-languages.python.data-types.numbers.float]]

## Arithmatic

```python
    10 + 3 # 13
    10 - 3 # 7
    10 * 3 # 30
    10 ** 3 # 1000
    10 / 3 # 3.3333333
    10 // 3 # 3 -> floor division - no decimals and returns on int
    10 % 3 # 1 -> modulo operator - retturn the reminder. Good for deciding if number is even or odd.
```

## Basics Functions

```python
    pow(5, 2) # 25 -> like doing 5**2
    abs(-50) # 50
    round(5.46) # 5
    round(5.468, 2) # 5.47 -> round to nth digit
    bin(512) # '0b1000000000' -> binary format
    hex(512) # '0x200' -> hexadecimal format
```

## Converting Strings to Numbers

```python
    age = input("How old are you?")
    age = int(age)
    pi = input("What is the value of pi?)
    pi = float(pi)
```
