---
id: teehvdfesu99355lhaem0an
title: List Unpacking
desc: ''
updated: 1665262747478
created: 1665262268525
---
# list unpacking
If you want to unpack the first few elements of a list and don’t care about the other elements, you can:

First, unpack the needed elements to variables.
Second, pack the leftover elements into a new list and assign it to another variable.
By putting the asterisk (*) in front of a variable name, you’ll pack the leftover elements into a list and assign them to a variable. For example:

```python
    colors = ['red', 'blue', 'green']
red, blue, *other = colors

print(red) # red
print(blue) # blue
print(other) # ['green']
```