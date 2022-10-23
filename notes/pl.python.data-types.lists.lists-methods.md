---
id: v90223wxhhstifi81e2d5vm
title: Lists Methods
desc: ''
updated: 1665261687652
created: 1665261222812
---


## List Methods

### Add to List
```python
    my_list * 2 # [1, 2, '3', True, 1, 2, '3', True]
    my_list + [100] # [1, 2, '3', True, 100] -> doesn't mutate original list, create new one
    my_list.append(100)  # None -> Mutates original list to [1, 2, '3', True, 100] or <list> += [<el>]
    my_list.extend([100,200]) # None -> Mutates original list to [1, 2, '3', True, 100, 200] 
    my_list.insert(2, '!!!!') # None -> [1, 2, '!!!!','3', True,]
    ' '.join(['Hello','There']) # 'Hello There' -> Joins elements using string as separator.
```

### Copy a List 
```python
    basket =['apples','pears','oranges']
    new_basket = basket.copy()
    new_basket2 = basket[:]
```

### Remove from List
```python
    [1,2,3].pop() # 3 -> mutates original list, default index in the pop method is -1 (the last item)
    [1,2,3].pop(1)# 2 -> mutates original list
    [1,2,3].remove(2) # [1,3] -> removefirst occurrence of item or raises ValueError.
    [1,2,3].clear() # None -> mutates original list and returns all items: [] 
```

### Ordering 
```python
    [1,2,5,3].sort() # None -> mutates list to [1,2,3,5]
    [1,2,5,3].sort(reverese=True) # None -> mutates list to [5,3,2,1]
    sorted([1,2,5,3]) # [1,2,5,3] -> new list created
    list(reversed([1,2,5,3])) # [3,5,2,1] -> reversed() returns an iterator
```

### Useful operations
```python
    1 in [1,2,5,3] # True
    min([1,2,3,4,5]) # 1
    max([1,2,3,4,5]) # 5
    sum([1,2,3,4,5]) # 15
    print(list(range(100))) # [0,1,2,3,4,5,...up to 99] -> range syntax: range(start, stop, step)
```

### exercise
[exercise Repl](https://repl.it/@aneagoie/lists-3)