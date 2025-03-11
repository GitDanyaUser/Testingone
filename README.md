# cus_depr

`cus_depr` is a Python library that provides shortcuts for `warnings`.

## Installation

You can install it with PyPI. Enter this in your terminal:

```bash
pip install cus_depr
```

## Usage

`cus_depr` offers two decorators to mark deprecated functions and suggest alternatives.

### Example 1: Marking a function as deprecated

```python
from cus_depr import deprecated

@deprecated
def old_func():
    print("This is an old function.")
```

### Example 2: Suggesting an alternative function

```python
from cus_depr import uinstead

@uinstead("new_func")
def old_func():
    print("This is an old function.")

def new_func():
    print("This is a new function.")
```

## Contributing

Contributions are welcome! Please create a pull request or submit an issue for any improvements or suggestions.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, please contact [your email/contact link].
```
