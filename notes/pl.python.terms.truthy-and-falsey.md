---
id: pvlb8la4m3usr8pbyqjdt74
title: Truthy and Falsey
desc: ''
updated: 1665341006271
created: 1665340464584
---
We use "truthy" and "falsy" to differentiate from the bool values True and False. 

A "truthy" value will satisfy the check performed by if or while statements. 

A "falsy" value are:
* [[None|pl.python.data-types.none]]  
* False   

* Numbers that are numerically equal to zero, including:
    * `0`
    * `0.0`
    * `0j`
    *     decimal.Decimal(0)
    * fraction.Fraction(0, 1)

* Empty sequences and collections, including:
    * [] - an empty list
    * {} - an empty dict
    * () - an empty tuple
    * set() - an empty set
    * '' - an empty str
    * b'' - an empty bytes
    * bytearray(b'') - an empty bytearray
    * memoryview(b'') - an empty memoryview
    * an empty range, like range(0)

* objects for which:
    * obj.__bool__() returns False
    * obj.__len__() returns 0, given that obj.__bool__ is undefined

[more Documentation](https://docs.python.org/3/library/stdtypes.html#truth-value-testing)