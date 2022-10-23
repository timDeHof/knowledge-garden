---
id: 7y61gtehg8l6yrpbfi0ygfe
title: Filter
desc: ''
updated: 1665971064840
created: 1665970574936
---
: Construct an iterator from those elements of _iterable_ for which the function returns true.
: _iterable_ may be either a sequence, a container which supports iteration, or an iterator. 
: If _function_ is `None`, the identity function is assumed, that is, all elements of _iterable_ that are false are removed.

## syntax
```python
filter(function, iterable)
```

## example
```python
def only_odd(item):
    return item % 2 != 0
    
print(list(filter(only_odd, [1,2,3]))) # [1,3]         
```

[more information](https://docs.python.org/3/library/functions.html#filter)