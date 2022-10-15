---
id: gu5al0x2kngi5nt0xfwg1qe
title: Objects
desc: ''
updated: 1665849762051
created: 1665522117140
---
:are created using the **class** keyword

**class**
:can be descriped as an object's bluprint, description, or definition.

**method** 
: our functions in a object


## creating our own Objects
```python
class PlayerCharacter:
    def __init__(self, name):
        self.name = name # attributes

    def ren(self): 
        print('run') # method

player1 = PlayerCharacter('Cindy') # instance of PlayerCharacter
print(player1.name)

```