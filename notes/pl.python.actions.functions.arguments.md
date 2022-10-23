---
id: afhqe0z1wpcj8gi0ewzfq4y
title: Arguments
desc: ''
updated: 1665424869228
created: 1665423575727
---
## Arguments
:An argument is a value that is passed to a function when it is called. It might be a variable, value or object passed to a function or method as input. They are written when we are calling the function.
## Types of arguments
1. [[positional arguments|pl.python.actions.functions.arguments.positional]]
2. [[keyword arguments|pl.python.actions.functions.arguments.keyword]]

## defining and calling a function with arguments
Arguments are the values passed inside the parenthesis of the function. A function can have any number of arguments separated by a comma.
```python
# A simple Python function to check
# whether x is even or odd
 
def evenOdd(x):
    if (x % 2 == 0):
        print("even")
    else:
        print("odd")
 
# Driver code to call the function
evenOdd(2) # output -> even
evenOdd(3) # output -> odd
```