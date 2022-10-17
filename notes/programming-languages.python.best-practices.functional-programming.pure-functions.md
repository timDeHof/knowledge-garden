---
id: 5d3yrosmt6puy3agpqf4j6j
title: Pure Functions
desc: ''
updated: 1665973910234
created: 1665968775287
---
: a function that always returns the same result for same arguments values and it has no side effects like modifying an argument(or global variable) or outputing something. 

```python
def multiply_by2(list):
    new_list =[]
    for item in list:
        new_list.append(item*2)
    return new_list

print(multiply_by2([1,2,3])) # => [2,4,6]    
```
## common functions
1. [[map()| programming-languages.python.best-practices.functional-programming.pure-functions.map]]
2. [[filter()|programming-languages.python.best-practices.functional-programming.pure-functions.filter]]
3. [[zip()| programming-languages.python.best-practices.functional-programming.pure-functions.zip]]
4. [[reduce()| programming-languages.python.best-practices.functional-programming.pure-functions.reduce]]

[more information](https://www.geeksforgeeks.org/pure-functions/)

## Practice
[Exercise](https://repl.it/@aneagoie/functional-1)
[my solution](https://replit.com/@tdehof/functional-1#main.py)
[solution](https://repl.it/@aneagoie/functional)