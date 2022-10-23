---
id: 71i0m1g2z80thna6016xqfw
title: Mro
desc: Method Resolution Order
updated: 1665875073419
created: 1665874564326
---
**MRO - Method Resolution Order**: denotes the way a programming language resolves a method or attribute. In python, method resolution order defines the order in which the base classes are searched when executing a method. First, the method or attribute is searched within a class and then it follows the order we specified while inheriting. This order is also called Linearization of a class and set of rules are called *[MRO]:Method Resolution Order. While inheriting from another class, the interpreter needs a way to resolve the methods that are being called via an instance. 
## To get the MRO of a class
use either `__mro__` attribute or `mro()` method to display the order in which methods are resolved.

```python
    class A:
        num = 10
    
    class B(A):
        pass

    class C(A):
        num = 1
    
    class D(B, C):
        pass    
```
```mermaid
graph TD;
    A --> B;
    A --> C;
    B --> D;
    C --> D;
```
## output
```python
print(D.mro()) # [<class '__main__.D'>, <class '__main__.B'>, <class '__main__.C'>, <class '__main__.A'>, <class 'object'>]
```

## Lookup Order
**D -> B -> C -> A**
: Python follows depth-first order to resolve the methods and attributes.


[more info](https://www.geeksforgeeks.org/method-resolution-order-in-python-inheritance/)

[MRO Algorithm](http://www.srikanthtechnologies.com/blog/python/mro.aspx)
