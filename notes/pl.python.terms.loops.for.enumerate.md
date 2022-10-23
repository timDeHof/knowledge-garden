---
id: lqceapn6l0urwk1levw7ace
title: Enumerate
desc: ''
updated: 1665348353439
created: 1665347956954
---
# enumerate

The ```enumerate()``` function takes a collection (e.g. a tuple) and returns it as an enumerate object.

The ```enumerate()``` function adds a counter as the key of the enumerate object.

## syntax
enumerate(iterable, start)

## parameters
| **Parameter** |                             **Description**                            |
|:-------------:|:----------------------------------------------------------------------:|
|    iterable   |                           An iterable object                           |
|     start     | A Number. Defining the start number of the enumerate object. Default 0 |

## example
```python
for i, char in enumerate('Helllooo'):
    print(i, char) # 0 H
                   # 1 e
                   # 2 l
                   # 3 l
                   # 4 l
                   # 5 o
                   # 6 o
                   # 7 o
```    