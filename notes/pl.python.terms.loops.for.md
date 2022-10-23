---
id: wsvurxew3cpacuwhx7a19om
title: For
desc: ''
updated: 1665351155360
created: 1665345767044
---

## For loops

A **for** loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

This is less like the **for** keyword in other programming languages, and works more like an iterator method as found in other object-orientated programming languages.

With the **for** loop we can execute a set of statements, once for each item in a list, tuple, set etc.

### syntax
for var in [[iterable|pl.python.terms.iterables]]:
    # statements
    
### Example
```python
    fruits = ["apple", "banana", "cherry"]
    for x in fruits:
        print(x)
    # apple
    # banana
    # cherry    
```

## common for loop usage
![[pl.python.terms.loops.range]]

## best practice
![[pl.python.best-practices.end-parameter-in-print]]
[example](https://repl.it/@aneagoie/GUI-solution)
[more practice](https://repl.it/@aneagoie/loops)