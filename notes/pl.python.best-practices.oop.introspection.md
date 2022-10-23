---
id: 8jdbt1v6chf59b5hyvdaef9
title: Introspection
desc: ''
updated: 1665871655295
created: 1665871130391
---
:an ability to determine the type of an object at runtime.

## built-in functions
1. type(): This function returns the type of the object
2. dir(): This function returns the list of methods and attributes associated with the object
3. str(): This function convert everything into a string.
4. id(): This function returns a special id of an object.

## Methods for code introspection
| **Function** | **Description**                                                 |
|--------------|-----------------------------------------------------------------|
| help()       | It is used it to find what other functions do                   |
| hasattr()    | Checks if an object has an attribute                            |
| getattr()    | Returns the contents of an attribute if there are some.         |
| repr()       | Return string representation of object                          |
| callable()   | Checks if an object is a callable object (a function)or not.    |
| issubclass() | Checks if a specific class is a derived class of another class. |
| isinstance() | Checks if an objects is an instance of a specific class.        |
| sys()        | Give access to system specific variables and functions          |
| __doc__      | Return some documentation about an object                       |
| __name__     | Return the name of the object.                                  |