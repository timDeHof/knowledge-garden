---
id: yc8ps0nd4gjq62txyns4dgy
title: Map
desc: ''
updated: 1665970251649
created: 1665969583886
---
: Makes an iterator that computes the function using arguments from each of the iterables. 
: Stops when the shortest iterable is exhausted.

## syntax
```python
map(function, *iterables)
```

## example 
```python
def multiply_by2(item):
    return item * 2

print(list(map(multiply_by2, [1,2,3]))) # [2,4,6]
```

[more information](https://docs.python.org/3/library/functions.html#map)
