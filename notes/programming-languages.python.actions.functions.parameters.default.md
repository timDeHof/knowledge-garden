---
id: l6suzaqfjvuxbfueo2psg73
title: Default
desc: ''
updated: 1665424594105
created: 1665424436499
---
# Default parameters
:A default argument is a parameter that assumes a default value if a value is not provided in the function call for that argument.

```python
# Python program to demonstrate
# default arguments
 
 
def myFun(x, y=50):
    print("x: ", x)
    print("y: ", y)
 
 
# Driver code (We call myFun() with only
# argument)
myFun(10) # output -> x:  10 y:  50
```