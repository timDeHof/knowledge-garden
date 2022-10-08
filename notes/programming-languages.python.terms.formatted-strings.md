---
id: zsfww8p0blvnugu8uh8youi
title: Formatted Strings
desc: ''
updated: 1665192073081
created: 1665192063548
---

## String Formatting

```python
    name1 = 'Tim'
    name2 = 'Andrei'
    print(f"Hello there {name1} and {name2}") # 'Hello there Tim and Andrei' -> Newer way to do things as of python 3.6
    print("Hello there {} and {}".format(name1, name2)) # 'Hello there Tim and Andrei'
    print("Hello there %s and %s", %(name1, name2)) # Hello there Tim and Andrei -> you can also use %d, %f, %r for integers, floats, string representations of objects respectively
```