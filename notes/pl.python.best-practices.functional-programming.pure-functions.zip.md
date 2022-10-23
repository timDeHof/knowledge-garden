---
id: 3mzmq6vlw5ix9utx1l4k3r8
title: Zip
desc: ''
updated: 1665971506016
created: 1665971204427
---
: Iterate over several iterables in parallel, producing tuples with an item from each one.
: return: an iterator of tuples, where the _i_-th tuple contains the _i_-th element from each of the argument iterables.

## example
```python
for item in zip([1, 2, 3], ['sugar', 'spice', 'everything nice']):
   print(item) # (1, 'sugar')
               # (2, 'spice')
               # (3, 'everything nice')
```

[more info](https://docs.python.org/3/library/functions.html#zip)