---
id: oz0f4jnvihbl1n4uibkf3f5
title: Generators
desc: ''
updated: 1666131997991
created: 1666131006449
---
:defined like a normal function, but whenever it needs to generate a value, it does so with the yield keyword rather than return. If the body of a def contains yield, the function automatically becomes a generator function. 
**yield** keyword: returns a generator object to the one who calls the function which contains yield, instead of simply returning a value.
```python
def generator_function(num):
    for i in range(10):
        yield i 
for item in generator_function(1000):
    print(item)        
```
## performance 
useful when you calulating large amount of data(loop over a larger dataset)
[more info](https://www.geeksforgeeks.org/generators-in-python/?ref=lbp)
[more info](https://realpython.com/introduction-to-python-generators/)