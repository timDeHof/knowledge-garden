---
id: z6l2ue0k3nhs4cwcuthe6ve
title: Parameters
desc: ''
updated: 1665424885229
created: 1665422948470
---
## parameters
:A parameter is the variable defined within the parentheses during function definition. Simply they are written when we declare a function. 

![[Default parameters|programming-languages.python.actions.functions.parameters.default]]

### Defining and calling a function with parameters
If you're familiar with C/C++ or Java, you're probably thinking about the function's return type and the data type of its arguments. That is also possible in Python (specifically for Python 3.5 and above).

## syntax
```python
def function_name(parameter: data_type) -> return_type:
    """Doctring"""
    # body of the function
    return expression
```
## example
```python
def add(num1: int, num2: int) -> int:
    """Add two numbers"""
    num3 = num1 + num2
 
    return num3
 
# Driver code
num1, num2 = 5, 15
ans = add(num1, num2)
print(f"The addition of {num1} and {num2} results {ans}.")
```