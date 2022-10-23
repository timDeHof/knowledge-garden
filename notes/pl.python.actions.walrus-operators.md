---
id: d51icm3mx6d0wiuvk8yxgy9
title: Walrus Operators
desc: ''
updated: 1665429818236
created: 1665428994571
---
# walrus operators
:a way to assign to variables within an expression using the notation
## syntax
```python
    NAME:= expression
```
```python
    a = 'hellooooooo'
    if((n:= len(a)) > 10):
        print(f'too long {n} elements')
    while ((n := len(a)) > 1):
        print(n)
        a = a[:-1]
    print(a)
```
[more info](https://www.geeksforgeeks.org/walrus-operator-in-python-3-8/)