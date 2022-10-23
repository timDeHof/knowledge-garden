---
id: g240wnprpjfuzl2qqyrzk1p
title: While
desc: ''
updated: 1665349387866
created: 1665348499324
---

## syntax
while <condition that evaluates to boolean>:
    # action
    if <condition that evaluates to boolean>:
        break; # break out of while loop
    if <condition that evaluates to boolean>:
        continue; # continue to the next line in the block

## waiting until user quits
```python
msg =''
while msg != 'quit'
    msg = input("What should I do?")
    print(msg)
```

## example
```python
while True:
    response = input("say something: ")
    if (response == 'bye'):
        break
```