---
id: yi3816no037kbmfztmx6ub8
title: Modules
desc: ''
updated: 1666143025098
created: 1666140198218
---
:a file containing Python definitions and statements.

## different ways to define a module
1. A module can be written in Python itself.
2. A module can be written in **c** and loaded dynamically at run-time e.g (re(regular expression) module).
3. A built-in module is intrinsically contained in the interpreter, e.g itertools module.

## advantages of modules
1. **Simplicity**: Rather than focusing on the entire problem at hand, a module typically focuses on one relatively small portion of the problem. If you’re working on a single module, you’ll have a smaller problem domain to wrap your head around. This makes development easier and less error-prone.

2. **Maintainability**: Modules are typically designed so that they enforce logical boundaries between different problem domains. If modules are written in a way that minimizes interdependency, there is decreased likelihood that modifications to a single module will have an impact on other parts of the program. (You may even be able to make changes to a module without having any knowledge of the application outside that module.) This makes it more viable for a team of many programmers to work collaboratively on a large application.

3. **Reusability**: Functionality defined in a single module can be easily reused (through an appropriately defined interface) by other parts of the application. This eliminates the need to duplicate code.

4. **Scoping**: Modules typically define a separate namespace, which helps avoid collisions between identifiers in different areas of a program. 