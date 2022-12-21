# Python KT

## Fundamentals (Common for most programming language)

1. Data Types
2. Variables
3. Basic Operators
4. Decision Making
5. Loops
6. Arrays
7. Strings
8. Functions
9. File I/O
10. OOPs concepts

## Python specific concepts

1. Data structures - List, Dict, Tupple
2. CRUD on data structures
3. Looping techniques
4. Error handling
5. OOPs
6. RegEx
7. Custom modules/packaging
8. Virtual environment
9. Package management - pip
10. Generators (For large file parsing)
11. Run time argument
12. Error handling
13. Logging
14. Execution of shell script from Python vice versa.

## Common built in libraries

1. os
2. sys
3. shutil
4. subprocess
5. logging

## Style guide for Python

[PEP 8](https://peps.python.org/pep-0008/), standard is followed by open source communities.

## TeamForge to GitHub migration

In this project we have maintained PEP 8 standard.

## Tools written during the project

1. SVN type repository to Git repository by converting SVN features to Git features like trunk, tags, branches revisions.
2. Git repository (which was present in TeamForge) to Git (GitHub).

## New concepts in Migration project

1. [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage) for file size more than 50 MB
2. Executing bash script from Python script.
3. Components of SVN repository, how to convert those into Git components.

## Libraries used in Migration project

1. [requests](https://pypi.org/project/requests/)
2. [GitPython](https://gitpython.readthedocs.io/en/stable/tutorial.html)
3. [PyGithub](https://github.com/PyGithub/PyGithub)

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