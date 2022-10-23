---
id: qrskztk5ohuadybd6euglj5
title: Immutability
desc: ''
updated: 1665193278393
created: 1665193000934
---
# immutability 
In python, the string data types are immutable. Which means a string value cannot be updated. We can verify this by trying to update a part of the string which will led us to an error.
```python
    # Can not reassign 
t= "Tutorialspoint"
print type(t)
t[0] = "M"
```
When we run the above program, we get the following output −
```console
    t[0] = "M"
TypeError: 'str' object does not support item assignment
```

We can further verify this by checking the memory location address of the position of the letters of the string.

```python
    x = 'banana'

for idx in range (0,5):
    print x[idx], "=", id(x[idx])
```
When we run the above program we get the following output. As you can see above a and a point to same location. Also N and N also point to the same location.
```python
    b = 91909376
    a = 91836864
    n = 91259888
    a = 91836864
    n = 91259888
    a = 91836864
```