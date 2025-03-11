# Info
This is a documentation for my first library for Python, `cus_depr`
It do shortcuts for `warnings`

# Installation
You can install it with PyPI
Enter this in your terminal:
```bash
pip install cus_depr
```

# Examples
It has 2 decorators
## Example 1
```Python
from cus_depr import deprecated

@deprecated
def old_func():
    print("This is a old function.")
```
## Example 2
```Python
from cus_depr import uinstead

@uinstead("new_func")
def old_func():
    print("This is a old function.")

def new_func():
    print("This is a new function")
```
