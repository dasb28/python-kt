# Python KT - Day 2

## Day 1 summary

1. What is Python?
2. Installation and setup
   - Download Python from btondemand
   - Check if Python has been installed
   - Write a sample script
   - Run using command line
   - Install PyCharm
3. Variable
4. Data types `string` `int` `boolean`
5. Conditional statements `if`
6. Loops `for` using `range` method


## Python specific concepts

- Data structures - List, Dict, Tupple
- CRUD on data structures
- Error handling
- OOPs
- RegEx
- I/O Operations
- Package management - pip
- Run time argument
- Execution of shell script from Python.

## Practice

1. Create a class and add methods to add, remove and find using `list` data type.
<br>Example:
```python
class Stack:
    def add():
        # Your code
    
    def show():
        # Your code

stack = Stack()
stack.add(2)
stack.add(5)

stack.show()
# Output should be: 2, 5
```
2. If user tries to add more than 5 values in the Stack class, then raise a `ValueError`.
<br>Example:
```python
class Stack:
    def add():
        # Your code
    
    def show():
        # Your code

stack = Stack()
stack.add(2)
stack.add(5)
stack.add(6)
stack.add(7)
stack.add(8)

stack.add(9)
# Output should be:
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError
```
## Resources to learn 📚

1. [Python's official site (Recommended)](https://docs.python.org/3/library/index.html)
2. [Git LFS](https://github.com/git-lfs/git-lfs)
3. [Basic Python tutorial (YouTube Video)](https://www.youtube.com/watch?v=eWRfhZUzrAc)


## IDE

#### [VS Code](https://code.visualstudio.com/)

Recommended extensions

1. [Python (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
2. [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)
3. [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
4. [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

#### [PyCharm - Community Edition (Recommended)](https://www.jetbrains.com/pycharm/download/#section=windows)

PyCharm is a full-fledged IDE which comes with almost everything common which are needed for coding in Python.

Configure the virtual environment path in PyCharm which enables running scripts within the IDE.

[How to configure Python Interpreter](https://www.jetbrains.com/help/pycharm/configuring-python-interpreter.html)

> NOTE: Avoid installing project specific packages globally.