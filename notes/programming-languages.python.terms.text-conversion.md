---
id: guiru4fcep1hkke6u457e1b
title: Text Conversion
desc: ''
updated: 1665194852435
created: 1665179575480
---
| type conversion |                          Description                          |
|:---------------:|:-------------------------------------------------------------:|
|     int(str)    |              convert a string to a integer number             |
|    float(str)   |          convert a string to a floating-point number          |
|    bool(val)    | convert a value to a boolean value, either `True` or `False`  |
|     str(val)    |          return the string representation of a value.         |

## examples
```python
    a = str(100)
    b = int(a)
    c = type(b)
    print(c) 
```

```python
# age finder
 birth_year = input('what year were you born?)

 age = 2022 - int(birth_year)

 print(f'your age is: {age}')
```