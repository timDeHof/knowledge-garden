---
id: itvhhrjrfzdn9ogrhiwcxyt
title: Docstrings
desc: ''
updated: 1665427166250
created: 1665427000541
---
## Document String
:used to describe the functionality of the function. The use of docstring in functions is optional but it is considered a good practice.

### Adding Docstring to the function
```python
# A simple Python function to check
# whether x is even or odd
 
 
def evenOdd(x):
    """Function to check if the number is even or odd""" # <- docstring
     
    if (x % 2 == 0):
        print("even")
    else:
        print("odd")
 
 
# Driver code to call the function
print(evenOdd.__doc__)
```