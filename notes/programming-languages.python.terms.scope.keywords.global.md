---
id: v1v8vvl6wm7qporom64l6lc
title: Global
desc: ''
updated: 1665432985283
created: 1665430749398
---
# global
: a keyword that allows a user to modify a variable outside the current scope.

## Rules of global keyword:
* If a variable is assigned a value anywhere within the function’s body, it’s assumed to be a local unless explicitly declared as global.
* Variables that are only referenced inside a function are implicitly global.
* We use a global keyword to use a global variable inside a function.
* There is no need to use global keywords outside a function.

## Use of global keyword in Python
: To access a global variable inside a function, there is no need to use a global keyword.

## example
### Accessing global Variable From Inside a Function
```python
# global variable
a = 15
b = 10
 
# function to perform addition
def add():
    c = a + b
    print(c)
 
 
# calling a function
add() # 25 -> output
```
### Modifying Global Variable From Inside the Function
```python
a = 15
 
# function to change a global value
def change():
    # increment value of a by 5
    b = a + 5
    a = b
    print(a)
 
change() # unboundLocalError: local variable 'a' referenced before assignment
```
### Changing Global Variable From Inside a Function using global
```python
x = 15
  
def change():
    # using a global keyword
    global x
 
    # increment value of a by 5
    x = x + 5
    print("Value of x inside a function :", x)
 
change()
print("Value of x outside a function :", x)
# output
# Value of x inside a function : 20
# Value of x outside a function : 20
```

[more info](https://www.geeksforgeeks.org/global-keyword-in-python/)