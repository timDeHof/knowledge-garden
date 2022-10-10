---
id: k637mm4okzhnfqsn6jt6b80
title: Is Vs ==
desc: ''
updated: 1665345317345
created: 1665344796475
---
## ==
```python
    print( True == 1)         # True
    print('1' == 1)           # False  
    print([] == 1)            # False
    print(10 == 10.0)         # True
    print([1,2,3] == [1,2,3]) # True
```

## is
```python
    print( True is 1)         # False 
    print('1' is 1)           # False  
    print([] is 1)            # False
    print(10 is 10.0)         # False 
    print([1,2,3] is [1,2,3]) # False 
```
check for equal memory location

```python
    print( True is True)         # True 
    print('1' is '1')           # True  
    print([] is [])            # False
    print(10.0 is 10.0)         # True
    print([1,2,3] is [1,2,3]) # False 
```
## Reason
== check for equality unlike ``is`` which check if the location in memory is equal.