---
id: xftll3gfs1j1qg8ss32jgph
title: Lists
desc: ''
updated: 1665262782769
created: 1665242229441
---
Unlike strings, lists are mutable sequences in python.

```python
    my_list = [1,2,'3', True] # We assume this list won't mutate for each example below.
    len(my_list) # 4
    my_list.index('3') # 2
    my_list.count(2 # 1 -> count how many times 2 appears
```
## List Indexing
```python
    my_list[3] # True
    my_list[1:] # [2, '3',True]
    my_list[:1] # [1]
    my_list[-1] # True
    my_list[::1] # [1, 2, '3', True]
    my_list[::-1] # [True, '3', 2, 1]
    my_list[0:3:2] # [1,'3']

    # : is called slicing and has the format [ start : end : step]
```
![[programming-languages.python.data-types.lists.lists-methods]]

![[programming-languages.python.data-types.lists.list-unpacking]]

## Get First and Last element of a list
```python
    mList = [63,21,30,14,35,26,77,18,49,10]
    first, *x, last = mList
    print(first) # 63
    print(last) # 10
```

# Matrix
```python
    matrix = [[1,2,3],[4,5,6],[7,8,9]]
    matrix[2][0] # 7 -> Grab first of the third item in the matrix object
```
## Looping through a matrix by rows:
```python
    mx = [[1,2,3], [4,5,6]]
    for row in range(len(mx)):
        for col in range(len(mx[0])):
            print(mx[row][col]) # 1 2 3 4 5 6
```

# Transform into a list: 
```python
[mx[row][col] for row in range(len(mx)) for col in range(len(mx[0]))] # [1,2,3,4,5,6]
```