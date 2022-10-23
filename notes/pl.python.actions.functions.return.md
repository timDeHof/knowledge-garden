---
id: vwd2q9zi2bl8diaaadm99y1
title: Return
desc: ''
updated: 1665426028046
created: 1665425033127
---
## return
:used to end the execution of the function call and “returns” the result (value of the expression following the return keyword) to the caller. **The statements after the return statements are not executed.** If the return statement is without any expression, then the special value None is returned. A return statement is overall used to invoke a function so that the passed statements can be executed.
## rules
1. Should do one thing really well
2. should return something

### syntax
```python
def fun():
    statements
    .
    .
    return [expression]
```
![[pl.python.best-practices.returns-cant-be-used-outside-of-a-function]]