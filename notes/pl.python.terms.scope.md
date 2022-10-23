---
id: 4qbc73bwmkqnnh2p07k9vl5
title: Scope
desc: ''
updated: 1665432899195
created: 1665429878125
---
# scope
: what variables do I have access to?
### Think of scope as creating little new worlds

## Rules 
1. start with local
2. parent local?
3. Global
4. built in python functions

```python
a = 1

def confusion():
    a = 5
    return a

print(a)            # 1
print(confusion())  # 5
```
## keywords
* [[global|pl.python.terms.scope.keywords.global]]
* [[nonlocal|pl.python.terms.scope.keywords.nonlocal]]