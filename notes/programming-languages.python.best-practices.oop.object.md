---
id: gu5al0x2kngi5nt0xfwg1qe
title: Object
desc: ''
updated: 1665522117140
created: 1665522117140
---
## creating our own Objects
```python
class PlayerCharacter:
    def __init__(self, name):
        self.name = name # attributes

    def ren(self):
        print('run')

player1 = PlayerCharacter('Cindy') # instance of PlayerCharacter
print(player1.name)

```