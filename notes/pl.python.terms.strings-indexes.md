---
id: t19k6f1e817x772a36xmi5r
title: Strings Indexes
desc: ''
updated: 1665192805492
created: 1665192540163
---
# string indexes

## syntax
```python
    # [start : stop: stepover] -> default stepover is 1
```

## examples
```python
name = 'Tim Dehof'
    print(name[4]) #D
    print(name[:]) #Tim Dehof
    print(name[1:]) # im Dehof
    print(name[:1]) # T
    print(name[-1]) # f
    print(name[::1]) # Tim Dehof
    print(name[::-1]) # foheD miT
    print(name[0:10:2]) # TmDhf
    # : is called slicing and has the format [ start : end : step]
    ```