---
id: 1mnbnj3fka0g0rziqc1kki4
title: Error Handling
desc: ''
updated: 1666130594863
created: 1666126680736
---
Error in Python can be two types:
- Syntax errors: the problems due to which theprogram will stop the execution.
- Exceptions: appear when some internal events occur which changes the normal flow of the program. [Built-in Exceptions](https://docs.python.org/3/library/exceptions.html)

## ways to handle errors:
 - try/except block
 ```python
 while True:
    try:
        age = int(input('what is your age?'))
        print(age)
    except ValueError:
        print('please enter a number')
    except ZeroDivisionError:
        print('please enter age over zero')
    else:
        print('thank you!')
        break
    finally:
        print('ok, I am finally done')    
 ```
 

[more information](https://www.geeksforgeeks.org/python-exception-handling/)