---
id: t0b82m1qmh9x0wp1ji7oh98
title: File Io
desc: "File Input and output"
updated: 1666658097971
created: 1666652135476
---

# working with files in python

To open the file, use the built-in `open()` function

## syntax

```python
    with open('data.txt', 'r') as f:
        data = f.read()
```

`open()` : takes a filename and a mode as its arguments.

- `"r"` - Read - Default value.Opens a file for reading, error if the file does not exist
- `"w"` - Write - Opens a file for writing, creates the file if it does not exist
- `"a"` - Append - Opens a file for appending, creates the file if it does not exist
- `"x"` - Create - Creates the specified file, returns an error if the file exists
  In addition you can specify if the file should be handled as binary or text mode
- `"t"` - Text - Default value. Text mode
- `"b"` - Binary - Binary mode (e.g. Images)

  [more info](https://www.w3schools.com/python/python_file_open.asp)

`read()` : method for reading the content of the file
: by default it returns the whole text, but you can also specify how many characters you want to return:

### example

Return the 5 first characters of the file

```python
f = open("dempfile.txt", "r")
print(f.read(5))
```

`readline()` : method for returning one line of the file

```python
    f = open("dempfile.txt","r")
    print(f.readline())
```

![[pl.python.best-practices.file-io.close-files]]

## Write to a file

## appeand to a file

## file paths

two ways to specify a file path

- absolute path: always begins with the root folder
- relative path: relative to the program's current working directory

### pathlib

## errors

```python
try:
 with open('sad.txt', mode='r') as my_file:
    print(my_file.read())
except FileNotFoundError as err:
    print('file does not exist')
    raise err
except IOError as err:
    print('')
```
