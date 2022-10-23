---
id: 2f25wv9e7lxqnbj9q99asz9
title: Decorators
desc: ''
updated: 1666126448855
created: 1666119350897
---
: a very powerful and useful tool in Python since it allows programmers to modify the behaviour of a function or class.
: In Decorators, functions are taken as the argument into another function and then called inside the wrapper function.

## syntax
```python
@gfg_decorator
def hello_decorator():
    print("Gfg")

'''Above code is equivalent to -

def hello_decorator():
    print("Gfg")
    
hello_decorator = gfg_decorator(hello_decorator)'''
```
gfg_decorator: a callable function that will add some code on the top of some another callable function., hello_decorator function and return the wrapper function.

<details>
<summary>Why Do We Need Decorators?</summary>
<br>
[when you want to add logging, test performance, perform caching, verify permissions, and so on.](https://www.freecodecamp.org/news/python-decorators-explained-with-examples/#:~:text=You'll%20use%20a%20decorator,same%20code%20on%20multiple%20functions.)
</details>

[practice](https://replit.com/@tdehof/decorators2-exercise#main.py)
[solution](https://repl.it/@aneagoie/decorators-1)
[more information](https://www.geeksforgeeks.org/decorators-in-python/)