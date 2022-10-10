---
id: y9y6m71f5d5b8alkgebet0p
title: Iterables
desc: ''
updated: 1665346874459
created: 1665346103408
---
## iterable- list, dictionary, tuple, set, string.

## iterated - one by one chack each item in the collection.

### for objects like dictionary
```python
user = {
    'name': 'Golem',
    'age': 5006,
    'can_swim': False
}


for item in user.items():
    print(item) # ('name','Golem'), ('age',5006), ('can_swim', False) -> prints out the object's items as tuples 

for key, value in user.items():
    print(key, value) # name Golem , age 5006, can_swim False -> tuple unpacking

for item in user.values():
    print(item) # Golem, 5006, False -> prints out only the values 
    
for item in user.keys():
    print(item) # name, age, can_swim -> prints out only the keys
```
