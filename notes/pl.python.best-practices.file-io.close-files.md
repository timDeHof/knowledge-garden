---
id: 3tbahu6gv90oy82tt76vqtn
title: Close Files
desc: ""
updated: 1666656232143
created: 1666656064406
---

It is a good practice to close files when you are done with it.

```python
f = open('demofile.txt',"r")
print(f.readline())
f.close()
```

**Note** : You should always close your file, in some cases, due to buffering, changes made to a file may not show until close the file.
