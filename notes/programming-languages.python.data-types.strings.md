---
id: vq518sz3fpazaqab1lnid8a
title: Strings
desc: ''
updated: 1664986526896
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

    print('Hi there ' + 'Timmy') # 'Hi there Timmy' -> This is called string concatenation
    print('*' * 10) # **********
 ```

## Basic Functions

```python
    print(len('turtle')) # 6 -> len() is function that returns the number of items in an object. 
```

## Basic Methods

```python
    print(' I am alone '.strip()) # 'I am alone' -> Strips all whitespace characters from both ends.
    print('On an island'.strip(d)) # 'On an islan' -> Strips all passed characters from both ends.
    print('but life is good!'.split()) # ['but', 'life', 'is', 'good!']
    print('Help me'.replace('me', 'you')) # 'Help you' -> Replaces first with second parameter
    print('Need to make fire'.startswith('Need')) # True
    print('and cook rice'.endswith('rice')) # True
    print('bye bye'.index(e)) # 2
    print('still there?'.upper()) # 'STILL THERE?'
    print('HELLO?!'.lower()) # hello?!
    print('ok, I am done.'.capitalize()) # 'Ok, I am done.'
    print('oh hi there'.find('i')) # 4 -> returns the starting index position of the first occurrence
    print('oh hi there'.count('e')) # 2S
```

## String Formatting

```python
    name1 = 'Tim'
    name2 = 'Andrei'
    print(f"Hello there {name1} and {name2}") # 'Hello there Tim and Andrei' -> Newer way to do things as of python 3.6
    print("Hello there {} and {}".format(name1, name2)) # 'Hello there Tim and Andrei'
    print("Hello there %s and %s", %(name1, name2)) # Hello there Tim and Andrei -> you can also use %d, %f, %r for integers, floats, string representations of objects respectively
```

## Palindrome check

```python
    word = 'reviver'
    p = bool(word.find(word[::-1]) + 1) # checks for the first occurance of reverese word in the string
    print(p) # True
```
