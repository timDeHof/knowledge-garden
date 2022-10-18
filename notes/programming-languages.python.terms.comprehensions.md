---
id: v3xnrbqqiia8dabqqzyaizj
title: Comprehensions
desc: ''
updated: 1666058244991
created: 1666056933925
---
: provide us with a short and concise way to construct new sequences (such as lists, set, dictionary etc.) using sequences which have been already defined.
## 4 types of comprehensions
1. List Comprehensions
    - basic structure : 
    ```python 
    output_list = [output_exp for var in input_list if (var satisfies this condition)]
    ```
2. Dictionary Comprehensions
    - basic structure:
    ```python
    output_dict = {key:value for (key, value) in iterable if (key, value satisfy this condition)}
    ```
3. Set Comprehensions
    
    - basic structure: similar to list comprehension
    ```python
    output_list = {output_exp for var in input_list if (var satisfies this condition)}
    ```
    - The only difference between them is that set comprehensions use curly brackets { }. 
4. Generator Comprehensions
    - basic structure: similar to the list comprehension
    ```python
    output_list = (output_exp for var in input_list if (var satisfies this condition))
    ```
    - One difference between them is that generator comprehensions use circular brackets whereas list comprehensions use square brackets.
    - The major difference between them is that generators don’t allocate memory for the whole list. Instead, they generate each value one by one which is why they are memory efficient.The major difference between them is that generators don’t allocate memory for the whole list. Instead, they generate each value one by one which is why they are memory efficient.

[more info](https://www.geeksforgeeks.org/comprehensions-in-python/)