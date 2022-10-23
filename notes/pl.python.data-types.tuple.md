---
id: zznatrruxitxjldv9eyup8x
title: Tuple
desc: ''
updated: 1665271804210
created: 1665270812915
---
Tuples are used to store multiple items in a single variable.

A tuple is a collection which is ordered and unchangeable.

Tuples are written with round brackets.

## syntax
```python
    my_tuple = ('apple','grapes','mango','grapes')
```
## Tuple unpacking
```python
apple, grapes, mango , grapes = my_tuple
```

## Basic functions
```python
    len(my_tuple) # 4
    my_tuple[2] # mango
    my_tuple[-1] # 'grapes'
```

## Immutability
```python
    my_tuple[1] = 'donuts' # TypeError
    my_tuple.append('candy') # AttributeError
```

## Methods
```python
    my_tuple.index('grapes') # 1
    my_tuple.count('grapes') # 2
```

## Zip
```python
    print(list(zip([1,2,3],[4,5,6]))) # [(1,4),(2,5),(3,6)]
```

## unzip
```python
    z = [(1,2),(3,4),(5,6),(7,8)] # some output of zip() function
    unzip = lambda z: list(zip(*z))
    unzip(z) 
```