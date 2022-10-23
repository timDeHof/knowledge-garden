---
id: m1qoxc8508jztl2rba7lopn
title: Dictionaries Methods
desc: ''
updated: 1665270637622
created: 1665267676741
---

## Dictionaries methods
```python
    print(len(thisdict)) # 3
    print(list(thisdict.keys())) # ['brand','model','year']
    print(list(thisdict.values())) # ['Ford','Mustang',1964]
    print(list(thisdict.items())) #[("brand","Ford"),("model","Mustang"),("year",1964)]
    thisdict['color'] = 'blue' # {'brand': 'Ford', 'model': 'Mustang', 'year': 1964, 'color': 'blue'}
    print(thisdict.get('year')) # 1964 -> Returns None if key does not exist.
    print(thisdict.get('years', 0)) # 0 -> Returns default (2nd param) if key is not found 
    print(thisdict.update({'years': 1968}) # {'brand':'Ford','model':'Mustang', 'year': 1968, 'color': 'blue'}
    thisdict.clear() # {} -> Returns an empty dictionary  
```
[more Dictionary methods](https://www.w3schools.com/python/python_dictionaries_methods.asp)