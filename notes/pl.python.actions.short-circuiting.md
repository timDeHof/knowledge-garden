---
id: 3cqt5mlh2o1nimub1jfsju2
title: Short Circuiting
desc: ''
updated: 1665342934605
created: 1665341635723
---
stoppage of execution of boolean operation if the truth value of expression has been determined already.

The evaluation of expression takes place from left to right. In python, short-circuiting is supported by various boolean operators and functions. 

## Short-Circuiting in Boolean Operators
| **OPERATION** |              **RESULT**             |                                      **NOTES**                                     |
|:-------------:|:-----------------------------------:|:----------------------------------------------------------------------------------:|
|     X or Y    |    if X is False, then Y, else X    |        Y is executed only if X is False Else if X is true, X is the result.        |
|    X and Y    |     if X is false, then X else Y    |       Y is executed only if X is true; else, if X is false, X is the result.       |
|     not X     | if X is true, then false, else true | not has lower priority than non- boolean operators. e.g. not a == b => not(a == b) |

**or:** When the Python interpreter scans ```or``` expression, it takes the first statement and checks to see if it is true. If the first statement is true, then Python returns that object’s value without checking the second statement. The program does not bother with the second statement. If the first value is false, only then Python check the second value, and then the result is based on the second half. 
**and:** For an ```and``` expression, Python uses a short circuit technique to check if the first statement is false then the whole statement must be false, so it returns that value. Only if the first value is true, does it check the second statement and return the value. 
An expression containing and or stops execution when the truth value of expression has been achieved. Evaluation takes place from left to right.

## Examples
```python
    is_Friend = True
    is_User = True

    if is_Friend or is_User:
        print('best friends forever')

        
```

[reference](https://www.geeksforgeeks.org/short-circuiting-techniques-python/)