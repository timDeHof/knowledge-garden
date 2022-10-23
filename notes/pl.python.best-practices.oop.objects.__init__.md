---
id: as3kcgericaywvih0xacfu3
title: __init__
desc: ''
updated: 1665852438070
created: 1665851878435
---

: this is the most important method and called when an instance (object) of the class is created, using the class name as a function.
**self**
: the first parameter in the method.it refers to the instance calling the mthod.

**attributes**
: the attributes are pieces of data associated with them. 
e.g. (**Cat** instances have attributes **color** and **legs**. These can be accessed by putting a **dot**, and the attribute name after an instance.
In an __init__ method, **self.attribute** can therefore be used to set the initial value of an instance's attributes. )
```python
    class Cat:
    def __init__(self, color, legs):
        self.color = color
        self.legs = legs

    felix = Cat("ginger", 4)
    print(felix.color)

```