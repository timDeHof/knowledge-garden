---
id: vq518sz3fpazaqab1lnid8a
title: Strings
desc: ''
updated: 1665193663103
created: 1664978296616
---
# strings

- Strings in python are stored as sequences of letters in memory.

## examples

```python
    type('Hellloooooo') # str
    print('I\'m thirsty') # "I'm thirsty"
    "\n" # new line
    "\t" # adds a tab

    print('Hey you!'[4]) # y
    
    print('Hi there ' + 'Timmy') # 'Hi there Timmy' -> This is called string concatenation
    print('*' * 10) # **********
 ```
 
![[pl.python.terms.strings-indexes]] 

![[pl.python.data-types.strings.built-in-functions-&-methods]]

![[pl.python.terms.formatted-strings]]

## Palindrome check

```python
    word = 'reviver'
    p = bool(word.find(word[::-1]) + 1) # checks for the first occurance of reverese word in the string
    print(p) # True
```
